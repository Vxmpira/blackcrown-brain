# Prospector: List the exact click events needed to find the leak

Date: 2026-10-29
Task: List the exact click events needed to find the leak
For [[Herald]].

# Click events to locate the Korvus leak

**Goal ladder:** first paying customer (Korvus Operator).
**Baseline:** 40 visits, 2 clicks in 7 days. The leak could sit before the CTA (visitors never reach pricing), at the CTA, or after it (signup or checkout drop-off). These events separate the three.

## Caveat on registered jobs

I can't see the SERVER JOBS feed from this context, so I can't confirm which reports already exist. Before filing, check the feed. If a funnel rollup already covers any event below, extend that job instead of registering a new one. UTM tagging on outbound Korvus links shipped 2026-10-26 and is already standing, so don't refile it. Use the existing UTM parameters as the source key on every event.

## Events, in funnel order

| # | Event | Fires when | Where | Props | Reported by |
|---|---|---|---|---|---|
| 1 | `landing_view` | Page load on `/` | Korvus Flask `/` route | utm_source, utm_campaign, referrer | Funnel rollup (new or extended) |
| 2 | `scroll_50` / `scroll_90` | Page passes 50% and 90% depth, once each | `/` via a small script in korvus_landing.html | page, session | Funnel rollup |
| 3 | `pricing_impression` | Pricing section reaches 50% visibility, once per session | Pricing section of korvus_landing.html | section id, viewport width | Funnel rollup |
| 4 | `price_rendered` | Server-side price injection produced a visible dollar value | Pricing section, checked after injection | plan key (no dollar amounts stored) | Funnel rollup |
| 5 | `cta_click` | Any Korvus CTA on `/` is clicked | Each CTA in pricing section and hero | plan (observer, operator_annual, operator_monthly), position | Funnel rollup |
| 6 | `lodestone_click` | LodeStone link clicked from `/` | LodeStone CTA on korvus_landing.html | source | Funnel rollup |
| 7 | `signup_view` | `/signup` loads | `/signup` route | plan, utm carried through | Funnel rollup |
| 8 | `signup_submit` / `signup_error` | Form submitted or rejected | `/signup` form | plan, error code | Funnel rollup |
| 9 | `upgrade_view` | `/upgrade` loads (gated) | `/upgrade` route | plan | Funnel rollup |
| 10 | `checkout_start` | Click that redirects to Stripe checkout | `/upgrade` button | plan | Funnel rollup |
| 11 | `checkout_complete` | Stripe paid return | Read-only from Stripe, owner-held | plan, timestamp | Stripe read-only count in the rollup. Agents never touch billing. |

## Reporting job

Propose one daily server job, `korvus_funnel_daily`, that reads events 1 through 10 from the event log, joins by utm_source and utm_campaign, and writes a per-step count with conversion from the step above. Event 11 comes in as a read-only Stripe count. If the funnel rollup already exists, add these events to it and register nothing new.

## Expected first read

- Many `landing_view`, few `pricing_impression`: the leak is above the pricing section. Fix layout or copy before touching CTAs.
- `pricing_impression` high, `price_rendered` low: price injection is failing. This is a bug, not a conversion problem.
- `cta_click` high, `signup_view` low: the CTA routing is broken.
- `signup_view` high, `checkout_start` low: the signup-to-upgrade step loses people.

## Filing order

1. Owner confirms the event list and whether an existing job covers it.
2. One ask per page: first korvus_landing.html (events 2 through 6). Exact CURRENT anchors required. The signup and upgrade templates get their own asks once the audit confirms their file names. Don't guess names.
3. Rollup job filed once, after the event ask lands.

Revenue move for today: the `price_rendered` check. If prices aren't visibly rendering, no CTA fix matters.
