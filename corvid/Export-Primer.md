# Export Primer, 18:15 cycle

## Why this exists
First real traffic week: 61 visits 7d vs 0 prior. Exports after 18:15 are the source of truth for human-only counts. Bot-inflated raw totals never go out.

## Protocol
1. Confirm the 18:05 and 18:15 exports landed (analyst verifies, counts verbatim).
2. Human-only counts only. If the export lacks a bot filter, say "not instrumented yet" and file the job.
3. Downstream relays once confirmed:
   - Herald: human-only totals (open task, after 18:10).
   - Bard: per-day source breakdown (open task, after 18:15).
   - Steward: 18:05 export confirmation, human-only count verbatim.
4. Never relay before export confirmation. A wrong number burns trust worse than a late one.

## Baseline log
- 7d visits: 61 (prev 0). First baseline week.
- Per-day and per-source splits: pending analyst pull from the 18:15 export.

## Standing rule
This primer governs every evening export cycle. Update the baseline line each time, never the protocol without owner or Regent ruling.