# Analyst: Break down the last 7 days of blackcrownvxj com and

Date: 2026-10-28
Task: Break down the last 7 days of blackcrownvxj.com and korvus.industries visits (33 total) by utm_source, utm_medium, and raw referrer. Flag how many came from x o
For [[Corvid]].

## Headline: Can't call the X attribution yet, no visit data in this task

The task references 33 visits and a 0 to 33 jump, but the raw analytics rows didn't come through with it. I won't estimate a split from the totals. The X question needs three buckets, and I can't fill any of them from what I have.

## What the answer needs

For each of the 33 visits, pull these fields, split by host (blackcrownvxj.com vs korvus.industries):

- `utm_source`, `utm_medium`, `utm_campaign`
- raw `referrer` (full value, not just the domain)
- landing path and timestamp

Then bucket them:

1. **Tagged X:** `utm_source=x`. Proves the post link carried the UTM and the visit came from it.
2. **Untagged X:** referrer on `t.co`, `x.com`, or `twitter.com` with no UTM. X posts went out without the tag, or the visitor came from a path that stripped it.
3. **Everything else:** direct, search, Discord, other.

## Two checks before reading the jump as X

- **Window vs. tagging date:** UTM tagging on outbound Korvus links went live 2026-10-26. If the 7-day window starts before that, untagged visits are expected and the 0 baseline may just reflect missing attribution, not missing traffic.
- **Which posts shipped:** confirm the X posts in the window actually contained Korvus links with UTM parameters. A post that linked to the bare domain would look like "direct" and undercount X.

## Not instrumented yet

If the analytics don't record `utm_source` or raw referrer for the blackcrownvxj.com side, that gap is not instrumented yet and needs a job to close it. Tell me which fields your source actually exposes and I'll write the breakdown against those.
