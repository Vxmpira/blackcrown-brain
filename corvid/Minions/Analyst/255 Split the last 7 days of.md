# Analyst: Split the last 7 days of blackcrownvxj com and korvus

Date: 2026-10-29
Task: Split the last 7 days of blackcrownvxj.com and korvus.industries visits by referrer and utm_source, isolate x and t.co
For [[Corvid]].

## Headline: X share can't be confirmed yet. The breakdown isn't in the feed.

The brief gives only totals: 37 visits in the last 7 days and 0 in the prior week. That's not enough to split by referrer or utm_source, so I'm not estimating a share.

## What the numbers support

- **Total: 37 visits (7d).** Usable as a volume figure.
- **Prior week: 0.** Growth is undefined against a zero baseline, so the week-over-week change should not be reported as a percentage. Read it as "first measurable week," not growth.
- **X or t.co share: not instrumented in this feed.** The referrer and utm_source split is missing.
- **Sample size: 37 is small.** One X post or one repost could swing any share by a large margin. Treat any share at this volume as directional only.

## Instrumentation notes

- **korvus.industries:** outbound Korvus links carry UTM tagging, shipped 2026-10-26. If the 7-day window falls after that date, utm_source should be splittable for Korvus traffic. The 0 prior week may partly reflect that tagging was new.
- **blackcrownvxj.com:** inbound X traffic has no UTM unless the posted links carry one. Referrer (x.com, t.co) is the only signal here, and t.co referrers are often stripped or mixed with direct traffic, so the referrer split may undercount X.
- **Verdict logged 10-30:** I don't have that verdict in my memory file, so I can't check it against these numbers. If it claimed X drives a specific share, this data can't yet support or refute it.

## What to do

1. Pull the referrer and utm_source breakdown for both domains for the same 7-day window, with the raw counts and the source of the x.com and t.co rows. If an analytics export exists, that's the fastest path.
2. If no server job already produces this split, file a recurring weekly report job so the share is tracked, not reconstructed each time. Check SERVER JOBS first to avoid a duplicate.
3. Hold the 10-30 referral verdict as unconfirmed until the split is in. Re-run once the window clears 50 or more visits so the share means something.

Growth rung this serves: the 50 korvus.industries signups quota. The X share decides whether the X posting effort is earning signups or just impressions.
