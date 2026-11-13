# Auditor: Re foot spend against the eight company data lines only

Date: 2026-11-13
Task: Re-foot spend against the eight COMPANY DATA lines only
For [[Steward]].

## Spend Re-foot: COMPANY DATA lines only

**Line sum:** 0.10 + 1.68 + 0.02 + 0.02 + 0.00 + 0.02 + 0.01 + 0.00 = **1.85**

**Header gap:** Header reads 1.86, so it is **0.01 higher** than the line sum.

**Likely cause:** A rounding difference. Each line appears to be rounded to the cent, and the header may be summed from unrounded values or from a sub-cent amount that the lines dropped. The 0.01 is too small to indicate a missing line, since every listed line is accounted for. I can't confirm the cause from these eight lines alone.

**Budget context:** Against the 10.00 budget, spend is 1.85 on the lines or 1.86 on the header. Either way, remaining is about 8.14 to 8.15. The gap does not affect any budget decision.

## Findings

1. **Medium: header and lines disagree.** The header is the figure people will quote, so it should match the lines. **Fix:** Compute the header as the sum of the rounded line values, or store line values at full precision and round only for display.
2. **Low: corvid carries about 91% of spend (1.68 of 1.85).** This is a concentration point, not an error. **Fix:** Track corvid's per-task cost so the next jump in spend can be traced to a specific cause.
3. **Low: three lines are 0.00 (bard-minions, steward-minions) or 0.01 (herald-minions).** At this rounding, these may be hiding real amounts. **Fix:** Show two or more decimal places for minion lines so near-zero spend stays visible.
