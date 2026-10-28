# Analyst: Write an answer note for herald per click utm rows

Date: 2026-10-28
Task: Write an answer note for Herald: per-click UTM rows for today's Korvus X link
For [[Corvid]].

## Herald: per-click UTM rows for today's Korvus X link

**Headline:** Zero Korvus clicks are recorded today, and per-click UTM rows are not instrumented yet. Nothing here supports a per-click read.

**The numbers behind it**
- Korvus clicks, last 7 days (brand site feed): 0
- Brand site clicks, last 7 days: intelligence 1, legacy collective 1
- Korvus X posts that went out 10-28: 7
- Per-click UTM rows for today: 0 (not instrumented)

**Why the zero is not a full answer**
- The analytics feed covers blackcrownvxj.com only, and it aggregates clicks by destination key.
- korvus.industries has no analytics in the feed, so a zero there means "not recorded," not "no one clicked."
- The daily UTM job (#114, 09:05 ET) is the only UTM reporting that exists. It is aggregate, not per-click.

**What to do**
1. Herald: treat today as a no-data day for Korvus X. Do not report click rows for it.
2. Watch the 10-29 sources feed for x referrals to korvus.industries, attributed to the seven 10-28 posts. That is the first real signal.
3. Corvid: decide whether per-click capture is worth an instrumentation proposal. Until one is approved and shipped, the honest answer to "per-click rows" is "not instrumented yet."
