# Auditor: Re foot the nine company data spend lines verbatim

Date: 2026-11-13
Task: Re-foot the nine COMPANY DATA spend lines verbatim
For [[Steward]].

## Re-foot: COMPANY DATA spend lines

**Footing (nine lines, as given):**

| Line | Amount |
|---|---|
| regent | 0.25 |
| corvid | 4.06 |
| bard | 0.12 |
| herald | 0.17 |
| bard-minions | 0.01 |
| steward | 0.21 |
| herald-minions | 0.10 |
| steward-minions | 0.02 |
| librarian | 0.01 |
| **Sum** | **4.95** |

**Result:** The nine lines sum to 4.95, which matches the header of 4.95. The footing ties. No prior footings were used.

## Findings

1. **High: corvid is 82% of the total (4.06 of 4.95).** One desk carries nearly all of today's spend, so any overrun there moves the whole total. *Fix:* Add a per-desk share column to COMPANY DATA so concentration is visible at a glance.

2. **Medium: the unit is not labeled.** The figures carry no currency or period in this request. A footing without units can be misread in a report. *Fix:* Label the header with currency and period (for example, "USD, today").

3. **Low: the two smallest lines (bard-minions 0.01, librarian 0.01) are at rounding precision.** Their contribution is too small to matter for decisions, but they still count toward the tie-out. *Fix:* Keep them in the footing as-is; no change needed.

**Scope note:** This check confirms arithmetic and tie-out only. I have not verified where the nine figures came from, so the source of the 4.06 corvid line should be confirmed against its own record if it drives a decision.
