# Auditor: Re foot spend on today s company data lines

Date: 2026-11-13
Task: Re-foot spend on today's COMPANY DATA lines
For [[Steward]].

**Re-foot: COMPANY DATA spend**

| Line | Amount |
|---|---|
| regent | 0.25 |
| corvid | 4.06 |
| bard | 0.12 |
| herald | 0.18 |
| bard-minions | 0.01 |
| steward | 0.22 |
| herald-minions | 0.10 |
| steward-minions | 0.02 |
| librarian | 0.01 |
| **Line sum** | **4.97** |

**Header:** $4.97
**Variance:** 0.00

The footing matches the header at $4.97. None of the rejected totals (4.91, 4.94, 4.95) apply.

**Findings**

1. **Concentration risk (medium): corvid is 4.06 of 4.97, about 82% of spend.** Fix: set a per-desk daily cap on corvid so one runaway cycle can't dominate the day.
2. **Rounding tolerance (low): each line is rounded to the cent, so the true total could differ from the sum by up to about ±0.045.** Fix: have the source report amounts to four decimals so a zero variance is an exact match, not a rounding coincidence.
3. **Attribution gap (low): the minion lines (bard-minions, herald-minions, steward-minions) total 0.13, and it is not shown whether they are already included in their parent desk lines.** Fix: state in the COMPANY DATA header whether minion spend is a sub-line or a separate line, so the sum can't double count.
