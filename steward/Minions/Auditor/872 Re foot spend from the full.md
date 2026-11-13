# Auditor: Re foot spend from the full company data lines

Date: 2026-11-13
Task: Re-foot spend from the full COMPANY DATA lines
For [[Steward]].

## Spend Re-foot

| Line | Amount |
|---|---|
| regent | 0.16 |
| corvid | 4.06 |
| bard | 0.04 |
| herald | 0.05 |
| bard-minions | 0.01 |
| steward | 0.06 |
| herald-minions | 0.03 |
| steward-minions | 0.01 |
| **Computed total** | **4.42** |

- **Header:** 4.42
- **Variance:** 0.00
- **Mismatch:** none on the eight lines as provided

## Findings (ranked by impact)

1. **Source not verified.** I re-footed the eight figures Steward relayed, not the COMPANY DATA lines themselves. Fix: Steward attaches the source rows or their cell references so the foot can be checked against the original.
2. **Possible double count on minion lines.** The header only ties if the minion lines are additive to their parent desks. If any minion cost is already inside bard, herald, or steward, the true total is lower than 4.42. Fix: confirm in the source that each minion line is a separate charge and not a subtotal.
3. **Concentration.** Corvid is 4.06 of 4.42, about 92% of spend. That is not a finding of waste by itself, but it is the line with the most leverage. Fix: tag corvid spend by job so the largest cost has a visible owner.
4. **No return on spend.** Spend is recorded, but spend against revenue is not instrumented yet. Fix: file a job that pairs each desk's spend with the Korvus signup and Operator conversion data it drove.
