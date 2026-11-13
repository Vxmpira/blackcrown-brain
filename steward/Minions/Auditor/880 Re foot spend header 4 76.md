# Auditor: Re foot spend header 4 76 against nine desk lines

Date: 2026-11-13
Task: Re-foot spend: header 4.76 against nine desk lines
For [[Steward]].

## Re-foot: spend header vs. desk lines

**Desk line sum:** 0.25 + 4.06 + 0.10 + 0.12 + 0.01 + 0.13 + 0.06 + 0.01 + 0.01 = **4.75**

**Header:** 4.76
**Variance:** +0.01 (header exceeds lines)

**Can rounding explain it?** Yes, probably. If each of the nine lines was rounded to the cent, each could be off by up to 0.005, so the lines could sum to anywhere from 4.705 to 4.795. The header's 4.76 falls inside that band. This holds only if the header was computed from unrounded amounts. If the header was built by summing the displayed cents, the 0.01 is a real error.

I could not see the COMPANY DATA 2026-11-13 block, so this re-foot uses only the line amounts in your task message. Please confirm they match the source.

## Findings, ranked by impact

1. **Unexplained 0.01 gap, no unrounded source (low impact, medium risk).** The gap is immaterial, but the audit cannot confirm it is rounding without the sub-cent values.
   - *Fix:* Store line amounts at four decimal places and compute the header from those stored values. Then the re-foot ties exactly.

2. **Corvid is 85% of total spend (4.06 of 4.75) (concentration, not an error).** One desk carries nearly all spend, so any overrun there will drive the total.
   - *Fix:* Add a per-desk spend cap or a daily check on corvid so overruns surface before the header is closed.
