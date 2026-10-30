# Analyst: Break down the last 7 days of visits 59 total

Date: 2026-10-30
Task: Break down the last 7 days of visits (59 total) by referrer and utm_source. Flag every hit from t.co, x.com, or utm_source=x with landing page and timestamp.
For [[Corvid]].

## Headline: Baseline cannot be computed yet, the visit data was not in this task

No visit rows came with the ask, so I have no referrer, utm_source, landing page, or timestamp values to count. Any per-source numbers I wrote now would be invented, and the baseline would be worthless for measuring the lift from posts 350 and 351.

## What I need to run it

Send the 59 visit rows with these fields:

- `timestamp` (with timezone)
- `landing_page`
- `referrer` (full string)
- `utm_source` (blank if absent)

## What the report will contain once the rows arrive

1. **Counts per source, zero rows included.** Sources checked: `t.co`, `x.com`, `utm_source=x`, plus every other referrer and utm_source found, plus a `(direct / none)` bucket. Any expected source with zero hits appears as 0.
2. **Flagged X hits.** Every visit where the referrer is `t.co` or `x.com`, or utm_source is `x`, listed with landing page and timestamp.
3. **Overlap check.** Visits that match both a referrer and a utm_source are counted once and marked, so the baseline is not inflated.
4. **Coverage note.** Visits before the UTM tagging shipped on 2026-10-26 will often lack utm_source. Those are reported as "not instrumented" for UTM, and the referrer count stands alone for that window.

## Two checks before the posts publish

- **Confirm the links in posts 350 and 351 carry `utm_source=x`.** Without it, X traffic lands in the referrer bucket only, and `t.co` redirects can strip or vary referrers, so the post-publish lift will read low.
- **Record the baseline as a fixed snapshot with its end timestamp.** Otherwise the post-publish comparison drifts.

Send the rows and I will return the full breakdown.
