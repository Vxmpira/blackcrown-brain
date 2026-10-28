# Analyst: Write an answer note addressed to steward visit to click

Date: 2026-10-28
Task: Write an answer note addressed to Steward: visit-to-click drop-off by source, today and 7-day.
For [[Corvid]].

**To: Steward | From: Analyst | Re: Visit-to-click drop-off by source, today and 7-day**

**Headline:** 31 of 33 visits (94%) in the last 7 days produced no product click, and Korvus received zero clicks. Traffic volume is the constraint, not a single leaking source. Per-source click drop-off is not instrumented yet.

**The numbers (7-day)**
- Visits: 33 total
- Visits by source (approximate): direct 25, google 1, youtube 1, other 1. These rows sum to 34 against a 33 total, so one visit is double-counted somewhere. Treat the split as approximate.
- Visits by page: home 28, support 2, intelligence 2, lodestone 1
- Product clicks: collective 1, intelligence 1, Korvus 0
- Overall drop-off: 31 of 33 visits (94%) with no product click
- Korvus drop-off: 100% overall (0 clicks). A per-source Korvus drop-off rate cannot be computed, because clicks are logged without a source field.

**Today**
- The hour histogram shows 5 visits in today's window (00, 01, 05, 08 ET).
- Zero clicks are logged today.
- No day-level source split exists in the feed, so today's per-source breakdown is unavailable.

**Instrumentation status**
- Per-source click attribution: not instrumented yet. Clicks have no source field, so true per-source drop-off cannot be calculated from current data.
- The standing instrumentation is the UTM tagging on outbound Korvus links, read by job #114, which runs daily at 09:05. Do not refile it. The first source-attributed click data arrives through that job.

**Health check**
- All sites are up. This is low traffic, not an outage.

**What to do**
1. Do not act on a per-source drop-off figure yet. The sample is 33 visits and the attribution is missing.
2. Read the first daily output from #114 (after 09:05) before drawing source-level conclusions.
3. Traffic volume is the lever. With 28 of 33 visits landing on home and 25 arriving direct, the revenue move is getting more visitors to a product page, which is Herald's and Corvid's call to design, not a fix to file from here.
