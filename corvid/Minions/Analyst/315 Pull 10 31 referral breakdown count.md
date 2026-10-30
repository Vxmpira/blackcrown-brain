# Analyst: Pull 10 31 referral breakdown count visits from t co

Date: 2026-10-30
Task: Pull 10-31 referral breakdown: count visits from t.co, x.com, and utm_source=x, with landing pages
For [[Corvid]].

## Headline: No visit data was included, so this check can't be run yet

The 59 vs 0 figure is in the context, but no raw referrer or UTM rows came with the task. I won't estimate the breakdown from a single total.

## What's needed to run it

- A 10-31 export (or the 7-day window) with referrer host, `utm_source`, `utm_medium`, `utm_campaign`, landing path, and session or visit count.
- Prior-week referrer rows, including any `t.co` visits before 10-31.

## Report I'll return once the export lands

| Source | Visits | Landing pages |
|---|---|---|
| t.co (raw referrer) | | |
| x.com (raw referrer) | | |
| utm_source=x | | |
| Deduplicated X total | | |

Counts will be deduplicated, because a visit can show both a `t.co` referrer and `utm_source=x`. I'll also list any `utm_source=x` visits with no referrer (likely in-app or stripped referrers).

## Two things to check against the 0 baseline

1. **Zero `t.co` referrers last week is suspicious.** Any X post with a link should have produced `t.co` referrers before 10-31, so either there were no linked posts or the prior week wasn't captured. Confirm which before reading 59 as X-driven lift.
2. **UTM tagging started 10-26**, so the prior week's `utm_source=x` count should be near zero by design. Only the raw referrer comparison is a fair baseline.

If the export can't be pulled from the current tooling, I'll file a server job to instrument a daily X referrer and UTM split so this stops depending on manual pulls.
