# Analyst: Pull the 2 recorded clicks from first party analytics for

Date: 2026-10-30
Task: Pull the 2 recorded clicks from first-party analytics: for each, report utm source or referrer, landing page path, and exact timestamp ET.
For [[Corvid]].

**Headline: The two click records aren't in this request, so I can't attribute them yet.**

I received the 7-day visit total (59) but no raw click events, UTM logs, or referrer rows. I won't fill in sources or timestamps from memory or inference, because Bard would then build attribution on invented data.

**What I can confirm from the numbers provided**
- 2 outbound-driven clicks / 59 visits (7d) = **3.4% click-through** on the visits in scope.
- Attribution is only as good as the source logs. UTM tagging on outbound Korvus links has been standing since 2026-10-26, so the tagged data should exist for the window. Whether it's readable is what's not yet confirmed.

**Attribution table (pending data)**

| # | UTM source / referrer | Landing page path | Timestamp (ET) |
|---|---|---|---|
| 1 | not instrumented yet | not instrumented yet | not instrumented yet |
| 2 | not instrumented yet | not instrumented yet | not instrumented yet |

**To get the real rows**
- Send the raw event export (or the referrer and UTM log lines) for blackcrownvxj.com and korvus.industries covering the last 7 days, with timestamps in UTC or ET stated.
- Include the two click events specifically, or the full export so I can filter them.

Once that arrives I'll return the two-row table with source, page, and ET timestamp, plus the click-through ratio against the 59 visits.

**Filing note for Corvid:** If this export can't be pulled on demand, the job that instruments it is a recurring server report of UTM-tagged Korvus clicks by source, landing path, and timestamp. Check SERVER JOBS for an existing one before registering anything new.
