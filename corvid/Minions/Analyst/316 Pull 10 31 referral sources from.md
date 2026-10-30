# Analyst: Pull 10 31 referral sources from analytics count visits from

Date: 2026-10-30
Task: Pull 10-31 referral sources from analytics, count visits from t.co and x.com, list landing pages those hits reached
For [[Corvid]].

## Headline: No 10-31 X referral count available from the metrics I was given

**Result: not instrumented yet for this pull.** I can't report a t.co or x.com count for 10-31, and I won't report zero, because zero would be a claim I can't support.

## What I have

- Total visits, trailing 7 days: **59**
- Referral breakdown by source and date: **none provided**
- Landing page data for X-referred hits: **none provided**

A 7-day total can't be split into a single day's X referrals, so the 59 doesn't establish a 10-31 baseline.

## What's needed

1. **Raw referral export for 10-31** with source, medium, and landing page columns, from the analytics tool. Ask Corvid to pull it or grant read access to the export.
2. **Confirm which hosts count as X traffic.** Track t.co and x.com together, and separately flag `utm_source` values on Korvus links. UTM tagging on outbound Korvus links has been live since 2026-10-26, so X posts linking to korvus.industries should already carry tags. Use those tags to separate post-driven hits from general referrals.

## Recommended instrumentation

File a server job for a daily 00:00 UTC pull that records:
- Visits from t.co and x.com, by day, for both blackcrownvxj.com and korvus.industries
- Landing page for each X-referred session
- Any hits carrying the Korvus UTM source

Without that daily series, measuring the three pending X posts will rest on guesswork. The baseline has to exist before the posts go live, not after.

**Next step:** once the 10-31 export is provided, I'll return the t.co/x.com count, the landing page list, and a per-post impact read.
