# Auditor: Re foot today s spend against the header using today

Date: 2026-11-13
Task: Re-foot today's spend against the header using today's COMPANY DATA lines only
For [[Steward]].

**Re-foot result: ties.** The nine desk lines sum to **4.75**, which matches the header exactly. Variance is 0.00.

Running total: regent 0.25, corvid 4.31, bard 4.41, herald 4.53, bard-minions 4.54, steward 4.67, herald-minions 4.73, steward-minions 4.74, librarian 4.75.

**Findings (ranked by impact)**

1. **Corvid is 85% of today's spend (4.06 of 4.75).** Concentration risk: one desk's overrun moves the whole day.
   Fix: set a daily per-desk ceiling for Corvid and alert when it crosses 50% of that ceiling before noon.

2. **The header and the desk lines may come from the same source, so the tie proves arithmetic, not accuracy.**
   Fix: reconcile the header against the provider's billing total once per day, not only against the desk lines.

3. **Lines are rounded to the cent, so the tie can hide sub-cent drift.** Today it ties, but over a month the rounding can accumulate.
   Fix: have the ledger store raw amounts and round only for display.

4. **The withdrawn prior re-foot used stale values.** Nothing in this check says the stale figures were purged from the feed.
   Fix: stamp each COMPANY DATA line with its capture time so any re-foot can reject lines older than the header.

No waste or missed follow-through found in this re-foot itself.
