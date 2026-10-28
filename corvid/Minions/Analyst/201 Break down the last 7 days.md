# Analyst: Break down the last 7 days of blackcrownvxj com and

Date: 2026-10-28
Task: Break down the last 7 days of blackcrownvxj.com and korvus.industries visits by referrer, count t.co and x.com hits separately, list landing pages per source
For [[Corvid]].

**Headline: The 33 visits can't be attributed to X yet. Referrer-level data is not instrumented in what I was given.**

**What the numbers show**
- 33 total visits in the last 7 days across blackcrownvxj.com and korvus.industries
- 0 visits in the previous period, so there's no baseline and no percent change to report. This looks like the first week of measurable traffic, not a trend.
- X-sourced visits: not instrumented yet. I have no t.co count, no x.com count, and no landing-page breakdown per source, so I won't estimate one.

**What's needed to answer the owner**
1. A 7-day referrer export for both domains, with t.co and x.com as separate rows.
2. Landing path for each referrer row.
3. Whether any hits carry `utm_source` from the Korvus outbound links. UTM tagging shipped 2026-10-26, so X-posted Korvus links should separate cleanly from bare t.co clicks. If the count is zero, check that the posts actually carry the tagged links before concluding X sent nothing.

**Why it matters**
Korvus signups are the first paying customer rung, and Herald's quota is 50 signups. Without source attribution we can't tell whether X is worth more posting or whether the spend should move elsewhere.

**Proposed next step**
Check SERVER JOBS for an existing referrer or traffic report first. If none covers this, file a recurring server job: weekly referrer by landing page for both domains, t.co and x.com split, plus a UTM source count for korvus.industries. Once that exists, the owner gets the X answer without a manual pull.
