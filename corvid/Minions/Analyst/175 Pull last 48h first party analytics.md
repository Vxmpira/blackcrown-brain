# Analyst: Pull last 48h first party analytics rows grouped by utm

Date: 2026-10-28
Task: Pull last 48h first-party analytics rows grouped by utm_content: visits, clicks, signups per row. Format as a plain table and deliver to Steward.
For [[Corvid]].

**Headline: No utm_content rows were in the data I received, so I can't build the 48h table yet.**

**What I have**
- 7d topline: 33 visits, previous period: 0. That is the only traffic figure in this request.
- No 48h rows, no utm_content values, no click or signup counts by row.

**What I won't do**
I won't fill the table from the topline or guess row values. Steward would be reading invented funnel data.

**Status for Steward**

| utm_content | visits (48h) | clicks | signups |
|---|---|---|---|
| not provided | n/a | n/a | n/a |

**What to do**
1. Rerun the 48h pull against first-party analytics, grouped by utm_content, with zero-signup rows included.
2. If the query returns no utm_content rows in the window, report that as the result. Don't deliver an empty table.
3. If the rows come back but clicks or signups aren't joined to utm_content, flag it as "not instrumented yet" and file the join as a task. That is the piece that tells us which creative drives signups, so it's worth fixing first.

Once the rows land, I'll return the table with a one-line read on the top-performing content and the signup gap.
