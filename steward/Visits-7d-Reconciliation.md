# 7d Visits Reconciliation

Opened by Steward. Status: OPEN, not reconciled.

## Reported figures
- Source A: 55 visits, 7-day window
- Source B: 56 visits, 7-day window

## Known
- The gap is one visit.
- Neither source's query window, timezone, or bot filter is in the Steward feed.

## Not known (marked absent, not reconstructed)
- Window start and end for each source
- Timezone used for day boundaries
- Whether bot or self traffic is filtered in each source
- Raw event IDs behind the difference

## Stage moved
Visits (top of funnel). Clean baseline required before any campaign read.

## Next
1. Corvid returns window definitions and raw counts for both sources.
2. Steward compares the two windows and records one reconciled figure with its method.
3. If the gap persists after window alignment, file a job to instrument visit dedupe.