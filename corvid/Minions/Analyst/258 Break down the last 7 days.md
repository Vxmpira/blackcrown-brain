# Analyst: Break down the last 7 days of 37 visits by

Date: 2026-10-29
Task: Break down the last 7 days of 37 visits by referrer and utm_source, flag x.com and t.co share
For [[Corvid]].

**Headline: No verdict yet. The 37-visit split was not included in this task.**

I have the task and the framing, but no rows from first-party analytics. Any percentages I wrote now would be invented, so I'm not producing them.

**What's missing**
- Raw referrer and `utm_source` counts for the last 7 days (37 visits)
- A pre-10-30 baseline. "0 to 37" only shows a recovery if the prior window is also measured.
- The X post timestamps, so visits can be matched to posts after 10-30.

**What the verdict needs**
1. **Source split table:** visits and share % for each `utm_source` and each referrer host, with `x.com` and `t.co` on separate rows.
2. **Tagged vs untagged:** Korvus outbound links carry UTM tags (standing since 2026-10-26). If X-posted links were tagged, visits should show `utm_source` values. Visits with no UTM and a `t.co` referrer are likely X traffic, but that is an inference, not attribution.
3. **Referrer caveat:** `t.co` is X's redirect host, and many browsers strip or truncate referrers. A large "direct / none" bucket can hide X traffic, so the verdict must state how much of the 37 is unattributed.
4. **Post-to-visit match:** visits per post hour for posts after 10-30, compared with visits in hours with no post.

**Verdict rule I'll apply once rows arrive:** X drove the recovery only if x.com plus t.co plus tagged X `utm_source` account for a clear majority of the 37 visits and the increase starts after the first post. If the majority is unattributed or the timing does not match, the verdict is "not instrumented yet" for X specifically, with the gap named.

**Next step:** Corvid, please send the raw export (referrer, utm_source, utm_medium, utm_campaign, landing path, timestamp) for the 7-day window and the prior 7 days. If that export isn't available yet, the instrumentation gap goes back to the desk that owns analytics as a task.
