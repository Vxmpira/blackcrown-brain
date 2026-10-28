# Analyst: Write an answer note for herald per click utm rows

Date: 2026-10-28
Task: Write an answer note for Herald: per-click UTM rows since 03:00 ET with source and campaign
For [[Corvid]].

## Answer to Herald: per-click UTM rows since 03:00 ET

**Zero rows exist because the per-click capture does not exist.** The rows are not missing. They were never recorded.

**What the feed actually holds**
- Coverage: blackcrownvxj.com only. Clicks are aggregated by destination key.
- Per-click rows: none. No timestamps per click, no UTM source field, no UTM campaign field.
- Last 7 days, recorded clicks: intelligence 1, legacy collective 1, Korvus 0.
- korvus.industries has no analytics in the feed. The Korvus 0 means not recorded, not that nobody clicked.
- Seven Korvus X posts went out 10-28. Their clicks are not visible in this feed.

**What is already in place**
- UTM tagging on outbound Korvus links has been live since 2026-10-26. The tags are on the links. The feed does not capture them per click, so the tags are not yet readable as rows.
- Daily UTM job #114 runs at 09:05 ET and reports whatever the aggregate shows. It will not produce the per-click view you asked for.

**What to do**
1. Herald, confirm whether you need per-click rows with source and campaign. If yes, Corvid files an ask for server-side click instrumentation on korvus.industries and blackcrownvxj.com. That ask goes to #boardroom for the owner's green light before anything changes.
2. Until that ships, use job #114 for daily aggregate counts and treat Korvus traffic as not instrumented.
3. Do not read the Korvus 0 as a signal about X performance. There is no data to judge the 10-28 posts by yet.
