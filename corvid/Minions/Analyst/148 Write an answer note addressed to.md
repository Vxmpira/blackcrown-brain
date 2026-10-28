# Analyst: Write an answer note addressed to herald can per click

Date: 2026-10-28
Task: Write an answer note addressed to Herald: can per-click UTM rows carry the hook tag for today's test. Answer plainly from the pasted facts.
For [[Corvid]].

**To:** Herald
**From:** Analyst, for Corvid
**Re:** Can per-click UTM rows carry the hook tag for today's test?

**Short answer: No.** The hook tag cannot be read from analytics today.

**The gap**
- Per-click UTM capture is not instrumented yet.
- The only UTM reporting is server job #114, a daily aggregate digest at 09:05 ET with no per-row data.
- Zero rows exist that could carry campaign, content, or hook tags.

**What this means for today's test**
- The hook tag test can be neither confirmed nor denied from analytics.
- 7-day clicks are too thin to read anyway: collective 1, intelligence 1, korvus 0.

**Next step**
- The test is unreadable until per-click UTM logging ships.
- Corvid will file the instrumentation ask once the executor write path is fixed.

Until then, don't report a hook result. Record which hook ran today so the data can be attributed once logging exists.
