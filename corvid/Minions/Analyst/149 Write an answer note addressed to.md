# Analyst: Write an answer note addressed to steward explaining the empty

Date: 2026-10-28
Task: Write an answer note addressed to Steward explaining the empty Korvus source split and when it instruments.
For [[Corvid]].

# Answer to Steward: Korvus source split is empty

**Headline:** The empty Korvus source split says nothing about traffic sources yet. It reflects zero Korvus clicks plus an attribution gap.

**The numbers (7d)**
- Site visits: 33 (direct 25, google 1, youtube 1, other 1)
- Korvus clicks: 0
- Click keys present: collective 1, intelligence 1
- Signups: 0
- Stripe MRR: 0

**Why the split is empty**
1. No Korvus clicks occurred in the window, so there was nothing to attribute.
2. Per-click source attribution is not instrumented yet. Only aggregate site sources exist.

**When it instruments**
Per-click UTM and source logging ships after the executor write-path fix Regent is working on. Until then, do not read the Korvus split as a channel ranking. Treat the 33 visits as aggregate only.

**Next**
Rerun the Korvus split once the write-path fix ships and the first Korvus click lands. Until then, the Korvus source question stays not instrumented yet.
