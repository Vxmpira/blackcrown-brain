# Analyst: Break down the last 7 days of brand site and

Date: 2026-10-28
Task: Break down the last 7 days of brand site and korvus.industries visits by referrer and utm_source, isolate x.com and t.co traffic, report counts per landing page
For [[Corvid]].

## Headline: The breakdown can't be built from what I was given

I have two numbers: **33 visits in the last 7 days** and **0 in the prior week**. I don't have the raw referrer or utm_source rows, so I can't say how many came from x.com or t.co, and I can't report counts per landing page without guessing. Any split I wrote down would be invented.

## The numbers behind it

| Metric | Value | Status |
|---|---|---|
| Total visits, last 7d | 33 | Reported |
| Total visits, prior 7d | 0 | Reported |
| Visits by referrer (x.com, t.co) | Not instrumented yet | Needs raw logs |
| Visits by utm_source | Not instrumented yet | Needs raw logs |
| Visits per landing page | Not instrumented yet | Needs raw logs |

The prior week at 0 could mean the counter wasn't running before the 2026-10-26 UTM rollout, or that the tagged links only started getting traffic afterward. The totals alone don't tell me which, so I'd treat the 33 as a baseline, not a growth rate.

## What to do about it

1. **Pull the raw access logs for the last 7 days** from korvus.industries and the brand site, with referrer, full query string, and request path. Once those rows are in hand, I can split them by x.com, t.co, and utm_source, and count hits per route. Korvus public routes are /, /lodestone, /signup, /login, and /legal, plus any /p/ pages.
2. **File a recurring server job** that reports this breakdown weekly, so this question stops needing a manual pull. I'd check the SERVER JOBS feed first to confirm no existing job covers it before registering one.
3. **Check the x.com links separately:** UTM tags are only useful if the posts carry them. If the outbound X links aren't tagged, the utm_source split will undercount X regardless of how the logs look.

Send me the raw rows and I'll return the referrer, utm_source, and per-landing-page counts in the same format.
