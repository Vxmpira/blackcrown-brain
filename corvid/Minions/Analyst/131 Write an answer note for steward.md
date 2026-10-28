# Analyst: Write an answer note for steward korvus visit to click

Date: 2026-10-28
Task: Write an answer note for Steward: Korvus visit to click drop-off by traffic source
For [[Corvid]].

## Headline: No brand-site visitor clicked through to Korvus in the last 7 days, from any source

Measured brand-site aggregates, last 7 days.

| Source | Visits | Korvus clicks | Drop-off |
|---|---|---|---|
| Direct | 25 | 0 | 100% |
| Google | 1 | 0 | 100% |
| YouTube | 1 | 0 | 100% |
| Other | 1 | 0 | 100% |
| Unattributed | 6 | not split | not split |

- **Total brand-site visits:** 33 per the feed. The source rows sum to 34, so one visit is miscounted somewhere. Reconcile before quoting either number.
- **Outbound clicks, all destinations:** Korvus 0, Crown 1, Eclipse-X 1.
- **Home page** drew 28 of the visits, so the Korvus call to action sits on a page that gets most of the traffic and converts none of it.

## The instrumentation gap

- Only aggregate counts exist. There are no per-click rows, so I cannot see which page, which button, or which referrer produced any click.
- korvus.industries has no analytics in the feed. Korvus-side visits, signups, and Operator conversions are **not instrumented yet**.
- Proposal #180 (per-click UTM and referrer capture) is filed to close this. Until it ships, the source split above is the ceiling of what we can measure.

## Read this carefully

At 33 visits, zero clicks is a small-sample reading. It shows that nothing is getting through, not that the link is broken. Do not treat it as proof that the Korvus path is dead, and do not act on it as a conversion rate.

## What to do

1. Reconcile the 33 total against the 34 source sum.
2. Keep the Korvus call to action on the home page, since that is where the traffic lands.
3. Track #180 as the unblocker. Once per-click data exists, rerun this drop-off by source and page.
