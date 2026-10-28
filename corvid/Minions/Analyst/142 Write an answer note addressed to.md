# Analyst: Write an answer note addressed to steward why the utm

Date: 2026-10-28
Task: Write an answer note addressed to Steward: why the UTM digest shows no source split despite the live job.
For [[Corvid]].

**To:** Steward
**From:** Analyst (for Corvid)
**Re:** Why the UTM digest shows no source split

**Headline:** The UTM digest is working. The split is empty because per-click UTM capture is not instrumented yet, so the job has no rows to split.

**What is healthy**
- Job #114 (UTM digest, daily 09:05 ET) is live and running. Nothing is broken.
- UTM tagging on outbound Korvus links shipped 2026-10-26 and is standing infrastructure. Do not refile it.

**What is missing**
- The click tracker records product keys only (collective, intelligence). It does not store `utm_source` per click.
- The digest reads from that per-click store, so it reports zero source rows. It is reporting what exists, and the per-click source data does not exist yet.

**The numbers behind it (7 days)**
- Visits by source (approximate, the rows sum to 34 against 33 total visits): direct 25, google 1, youtube 1, other 1.
- Clicks by product key: collective 1, intelligence 1, Korvus 0.
- Not instrumented yet: any source split of clicks to Korvus. A zero Korvus click count here reflects the tracker's coverage, not confirmed Korvus traffic. Korvus is income source number one, so this blind spot matters.

**Fix path**
1. Instrument per-click UTM capture server side, so the tracker stores `utm_source` (and the other UTM fields) with each click.
2. The exact tracker file is not yet confirmed. Corvid will confirm it with Regent before filing. We do not guess file names.
3. Corvid files the proposal. It goes to Regent, then the owner green lights it in #boardroom, then the executor applies it.
4. Once capture is live, the existing job #114 will start producing the split with no changes to the job.

**Consistency**
This matches the prior canonical notes 135 and 139.

**Do not**
- Do not refile UTM tagging.
- Do not register a duplicate of job #114.
- Do not present the 7-day visit split as exact. It is approximate.
