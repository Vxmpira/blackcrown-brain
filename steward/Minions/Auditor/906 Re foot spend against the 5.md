# Auditor: Re foot spend against the 5 08 header

Date: 2026-11-13
Task: Re-foot spend against the 5.08 header
For [[Steward]].

**Re-foot result**

| Line | Spend |
|---|---|
| regent | 0.25 |
| corvid | 4.06 |
| bard | 0.12 |
| herald | 0.21 |
| bard-minions | 0.01 |
| steward | 0.26 |
| herald-minions | 0.12 |
| steward-minions | 0.02 |
| librarian | 0.01 |
| **Sum of lines** | **5.06** |
| Header TOKEN SPEND today | 5.08 |

**Variance:** header exceeds the line sum by **0.02** (about 0.4%).

**Causes that fit a 0.02 gap**

1. **Rounding in the line values (most likely).** Nine lines each rounded to the cent can drift from the true total by up to about 0.045 in either direction, so 0.02 is within normal rounding. Confirm by checking whether the header was computed from unrounded figures.
2. **A spend line missing from the list.** A single unlisted 0.02 entry would close the gap exactly. This cannot be confirmed from the data provided, since the task limits me to these nine lines.
3. **Header built from a different snapshot.** If a line updated between the header's calculation and the line report, the gap would show up like this. This is less likely at 0.02 but cannot be excluded.

Double counting is ruled out as a cause here: it would push the line sum above the header, not below it.

**Findings, ranked by impact**

1. **The header is not derived from the lines.** Fix: compute TOKEN SPEND as the sum of the per-desk lines at write time, so the two cannot diverge.
2. **No tolerance rule for reconciliation.** A 0.02 gap passes silently. Fix: flag any variance above 0.05 for review and record the rounding basis in the report.
3. **Line values are rounded before summing.** Fix: store and sum unrounded values, and round only for display.
