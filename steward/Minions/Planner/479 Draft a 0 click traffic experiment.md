# Planner: Draft a 0 click traffic experiment brief for ruling

Date: 2026-10-29
Task: Draft a 0-click traffic experiment brief for ruling
For [[Steward]].

# Experiment Brief: Korvus Landing Hero CTA (Visit to Click)

**Status:** Draft for ruling in #boardroom
**Owner:** Herald (copy and channel), Steward (deploy and readout)
**Rung:** First paying customer (top of funnel into Observer signup)

## Baseline (last 7 days)

| Stage | Count | Rate |
|---|---|---|
| Visits | 53 | n/a |
| Clicks onward | 2 | 3.8% visit to click |
| Signups | 0 | 0% click to signup |

The sample is too small to call a true baseline. Treat 3.8% as a working number only.

**Source gaps (PENDING, not PASS):**
- Per-page visit counts for korvus.industries are not confirmed as instrumented. PENDING Steward confirmation.
- Whether the 2 clicks came from tagged UTM links or untagged traffic is not confirmed. UTM tagging on outbound Korvus links is standing infrastructure, so this should be checkable. PENDING.
- Whether any paid or social channel changed during the last 7 days is not confirmed. PENDING Herald.

## The one change

Make the primary action above the fold on the Korvus landing page a single button labeled "Start free with Observer." Remove or demote competing links in the hero area (secondary links move below the fold). No price is written in the copy; prices stay server-injected as always.

- **Target file:** korvus:korvus_landing.html (hero section only)
- **Copy author:** Herald
- **Executor:** the proposal pipeline, one page, exact CURRENT anchors

**Hypothesis:** A single, clearly labeled action in the first screen raises the share of visitors who click onward.

## Success criteria

- **Primary metric:** visit to click rate.
- **Success:** at least 8% over the test window, with at least 150 visits in the window. A 2x lift over the working baseline is the bar for a green readout.
- **Guardrail:** signup rate per click must not fall below the pre-test level. Any drop triggers rollback review.
- **Sample size and significance threshold:** PENDING Steward power calculation before the readout is treated as decisive.

## Window and readout

- **Start:** the day the change goes live (pulls within about 2 minutes of merge to main).
- **Duration:** 14 days from go-live, or 150 visits, whichever comes later.
- **Readout date:** go-live date plus 14 days, posted to #boardroom by Steward with visits, clicks, signups, and the rate for both the old and new hero.
- **Calendar date:** to be filled when the owner rules and go-live is set.

## What the ruling triggers

If approved: Herald writes the hero copy, Steward files the single-page proposal to Regent, the owner green lights in #boardroom, and the executor applies one change to korvus_landing.html. Nothing else on the site, pricing, or channel mix changes during the window.

If rejected or deferred: nothing ships and the baseline stays as is.

## Explicitly out of scope

- No signup-flow changes (that stage is downstream and will be briefed separately).
- No pricing, Stripe, or billing changes.
- No claims about trading results. Copy stays educational and product-descriptive, with the not-advice disclaimer on product claims.
