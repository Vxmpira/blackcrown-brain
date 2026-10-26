# Quota Tracker

Purpose: single source of truth for daily quota numbers. Updated when Steward reports or when the daily digest job runs.

## Quotas in play
- Steward outbound sends: 50 per day (campaign plan in progress)
- Eclipse-X Discord joins: 100 (campaign in planning)
- Korvus Observer signups: experiment one pending

## Daily log
| Date | Steward sends | Eclipse-X joins | Observer signups | Operator conv | Notes |
|------|---------------|-----------------|------------------|---------------|-------|
| today | not reported yet | not instrumented yet | not instrumented yet | 0 | Daily digest job filed with Regent to automate this row |

## Rules
- Never invent a number. Blank cells get "not reported yet" or "not instrumented yet".
- Steward send counts land here the day they are reported, verbatim.
- Once the daily digest job is approved, this table mirrors the digest.