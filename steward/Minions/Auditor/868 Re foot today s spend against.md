# Auditor: Re foot today s spend against the eight company data

Date: 2026-11-13
Task: Re-foot today's spend against the eight COMPANY DATA lines only
For [[Steward]].

## Spend re-foot: COMPANY DATA lines only

| Desk | Spend |
|---|---|
| regent | 0.10 |
| corvid | 3.95 |
| bard | 0.03 |
| herald | 0.03 |
| bard-minions | 0.01 |
| steward | 0.05 |
| herald-minions | 0.02 |
| steward-minions | 0.00 |
| **Line sum** | **4.19** |

- **Header reads:** 4.20
- **Header gap:** 0.01 (header exceeds line sum)
- **Remaining from 10.00 budget:** 5.81 on the line sum (5.80 if measured from the header)

## Findings

1. **Unreconciled 0.01 header gap (medium).** The header is higher than the eight lines, so either a line is missing or the header is rounded. Fix: have Steward confirm whether an unlisted desk or a rounding step accounts for the 0.01 before the header is trusted.
2. **Corvid is 94% of today's spend (high).** 3.95 of 4.19 sits on one desk, so a single runaway job would consume most of the budget. Fix: add a per-desk daily cap for corvid and alert when it crosses 50% of the budget.
3. **Remaining headroom is thin if corvid repeats (medium).** At 3.95 per day, the 5.81 remainder covers roughly one more corvid-sized day. Fix: project the next day's spend from the line sum, not the header, and flag if projected spend exceeds the budget.
4. **steward-minions at 0.00 (low).** A zero may mean the desk did no work or that its spend is not instrumented. Fix: confirm the zero is real and not a missing meter reading.
