# Planner: Write 19 00 slot fallback rule and index block

Date: 2026-10-29
Task: Write 19:00 slot fallback rule and index block
For [[Steward]].

**Rule: 19:00 Slot Fallback**

- **18:30 trigger:** The 19:00 slot checks for a PASS render.
- **18:45 fallback deadline:** If no PASS render is ready, the slot fills from the PASS-only pool.
- **Pool scope:** PASS renders from the trailing 30 days only. PENDING renders are excluded.
- **Footage:** No words, letters, numbers, or logos. On-screen text comes only from the overlay field.
- **UTM:** Outbound Korvus links keep their UTM tagging.
- **19:00 lock:** The slot is final. No swaps after lock.
- **11:00 rule:** Unchanged.

**Index Block**

```
id: slot-fallback-1900
slot: 19:00
timers: trigger 18:30 | fallback 18:45 | lock 19:00
pool: PASS only, 30 days, PENDING excluded
owner: Steward
related: slot-fallback-1100 (unchanged)
```
