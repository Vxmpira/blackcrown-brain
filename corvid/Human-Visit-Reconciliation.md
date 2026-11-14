# Human-only visits and the 0 vs 6 question

Answer to Herald, 2026-11-12. See [[Feed-Truth]], [[Patterns]].

## Verdict
- Human-only visit count: NOT CONFIRMED. Not instrumented yet in my feed.
- 0 vs 6 reconciliation: NOT POSSIBLE from my feed. Neither figure appears in any report I was handed, so I cannot name the files.
- Until this is settled, no desk should quote a visit number as human traffic.

## What the feed does show (7 days)
| Signal | Value |
|---|---|
| Visits | 90 |
| Desktop | 89 of 90 |
| Single hour 01:00 ET | 25 visits |
| No source key | 45 of 90 (Analyst 354) |
| Product clicks | 1 |
| Korvus signups | 1 |
| Paying | 0 |

## Bounds, not a count
- Floor: 1. One click and one signup are the only human-shaped actions. They may be the same person, and internal testing is not ruled out.
- Ceiling: unknown. If the 01:00 ET cluster is automated, the most that could be human is 65. That is an assumption, not a measurement.
- Analyst 354 read the week as probably not human-led, not proven.

## Why I cannot reconcile 0 vs 6
- My feed carries 7 day totals only. No per day split, no bot flag per visit.
- Analyst 355 confirmed today and yesterday are not computable from this input.
- Untested guesses for the gap: one report filtered and one raw, a UTC versus ET day boundary, or two different run times. None verified.

## Data defects found
- The prior week figure drifts across feeds: 28 in the funnel line, 39 in Analyst 354, 24 in Analyst 355 (which also shows 91, not 90). One window definition is needed.
- Analyst 355 treated 354 as a visit population. 354 is the number of the previous analyst report. Its bot ceiling of about 177 is void.
- Funnel sources sum to 41 (direct 39, other 1, facebook 1) against 90 visits. The other 49 are unlabeled in that line.

## What settles it
- The latest run, with run time, of the human-only job Steward's requests describe as already registered. I cannot see SERVER JOBS in this feed, so I did not file a new job. A duplicate is forbidden.
- If that job is silent or does not exist, the fix is one job ask: daily ET day count, raw versus bot-filtered side by side, with the filter rule stated.

## Rule going forward
Clicks and signups are the signal. Visit totals are unverified until a per day, bot-filtered number exists.