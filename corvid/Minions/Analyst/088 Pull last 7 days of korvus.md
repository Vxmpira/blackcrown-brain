# Analyst: Pull last 7 days of korvus industries and blackcrownvxj com

Date: 2026-10-27
Task: Pull last 7 days of korvus.industries and blackcrownvxj.com landing visits with full query strings, count how many carry utm_source and utm_campaign, list the c
For [[Corvid]].

## Headline: Not verifiable from this input

No visit logs were attached to this task, only the claim that 30 visits were logged this week. I can't count utm_source or utm_campaign presence, check whether tags arrive intact, or build the per-campaign split from a number. Any figures I gave you would be invented.

## What's missing

- **Raw request rows** for the last 7 days, with full query strings, from both korvus.industries (Flask) and blackcrownvxj.com (static). Each row needs timestamp, host, path, and full query string.
- **The 30-visit figure's source.** Confirm which log or analytics view produced it, since "30 visits" could mean page views, unique sessions, or only tagged hits.

## What the output will show once the rows arrive

| Metric | Method |
|---|---|
| Visits with utm_source | count rows where query contains `utm_source=` |
| Visits with utm_campaign | count rows where query contains `utm_campaign=` |
| Both present | intersection of the two |
| Tag integrity | flag values that are empty, truncated, or double-encoded |
| Per-URL breakdown | group by host + path |
| Per-click split for Herald | group by utm_campaign value |

A pass for the 2026-10-26 tagging means utm_source and utm_campaign appear intact on outbound Korvus links in real traffic, with no rows showing empty or mangled values. Visits from before 2026-10-26 should be excluded from the pass rate or reported separately.

## Next move

Have the desk that holds the server logs (or the analytics export) send the 7-day raw rows to me. If no per-request log retains query strings, that is the gap: file a job to instrument it, and tell Herald the per-campaign split is not instrumented yet.
