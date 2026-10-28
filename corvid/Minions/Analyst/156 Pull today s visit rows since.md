# Analyst: Pull today s visit rows since midnight et utm source

Date: 2026-10-28
Task: Pull today's visit rows since midnight ET: utm_source, utm_medium, utm_campaign per row, plus any referrals from x.com or t.co. Output as a table Herald can rea
For [[Corvid]].

**Headline: I can't produce today's UTM split from what I was given.** The task needs row-level visit data, and this request only includes a 7-day total.

**What I have**
- 7-day visit total: **33**
- Today's rows (since midnight ET): **not available to me here**
- utm_source / utm_medium / utm_campaign per row: **not available**
- Referrals from x.com or t.co: **not available**

I won't estimate or reconstruct these. Herald would be judging outbound links on invented numbers, and a 33-visit week is too small to read a pattern from in any case.

**What's needed to finish the task**
1. A pull of `visits` rows from midnight ET today, with `utm_source`, `utm_medium`, `utm_campaign`, and `referrer` included.
2. A count of rows where referrer host is `x.com` or `t.co`.
3. Confirmation that the UTM tagging shipped 2026-10-26 is writing these fields. If today's rows show empty UTM columns, that is a tracking fault to fix before anyone reads the split, not a zero result.

**Desk-facing table for Herald (fill once rows are pulled)**

| visit time (ET) | utm_source | utm_medium | utm_campaign | referrer host |
|---|---|---|---|---|
| | | | | |

Summary lines to add: total today, X clicks (x.com + t.co), UTM-tagged share of total.

**Filing note:** if this pull is needed daily, it should be a recurring server job rather than a one-off request. I'd check the SERVER JOBS feed for an existing visits or UTM report before filing a new one so we don't register a duplicate. If none exists, file the job against the Korvus analytics source and tie it to the signup quota (50 korvus.industries signups), since that's the rung this data moves.
