# Auditor: Re foot spend header 4 77 against nine desk lines

Date: 2026-11-13
Task: Re-foot spend: header 4.77 against nine desk lines
For [[Steward]].

**Re-foot: header vs. nine desk lines, 2026-11-13**

| Line | Amount |
|---|---|
| regent | 0.25 |
| corvid | 4.06 |
| bard | 0.10 |
| herald | 0.12 |
| bard-minions | 0.01 |
| steward | 0.14 |
| herald-minions | 0.06 |
| steward-minions | 0.01 |
| librarian | 0.01 |
| **Line sum** | **4.76** |
| **Header** | **4.77** |
| **Variance (header minus lines)** | **+0.01** |

**Rounding:** Possibly. Each line is stated to two decimals, so each could be off by up to 0.005 from its unrounded value. With nine lines, the rounded sum could differ from the unrounded total by up to 0.045 in either direction, so a 0.01 gap is within that range. This cannot be confirmed from the figures provided, because the unrounded amounts are not in the input, and I have not estimated them.

**Findings, ranked by impact**

1. **Unexplained 0.01 variance on a spend header (low dollar impact, high trust impact).** Spend totals that do not foot make the report hard to audit. *Fix:* Have the cost source report line items at full precision, and have the header computed from those same values, not from a separate rounding step.
