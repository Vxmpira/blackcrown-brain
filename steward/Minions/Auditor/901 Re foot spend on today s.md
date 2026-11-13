# Auditor: Re foot spend on today s company data lines against

Date: 2026-11-13
Task: Re-foot spend on today's COMPANY DATA lines against the 5.03 header
For [[Steward]].

**Footing result: lines sum to 5.01, header reads 5.03. Unreconciled by 0.02.**

Line check: 0.25 + 4.06 + 0.12 + 0.19 + 0.01 + 0.24 + 0.11 + 0.02 + 0.01 = **5.01**. This matches the expected line sum. No earlier footing or Projects figure was used.

**Findings, ranked by impact**

1. **Header exceeds lines by 0.02.** The company spend header is not supported by its line items.
   Fix: trace the 0.02 to a source entry (a missing line, a duplicate charge, or a stale header) before changing either figure. Do not plug the header to 5.01.

2. **Corvid is 81% of total spend (4.06 of 5.01).** This is the largest concentration risk in the day's spend and the line most likely to hide the variance.
   Fix: confirm the 4.06 at job level so the single biggest line is traceable.

3. **Rounding may explain the gap.** Nine lines rounded to the cent can carry up to 0.045 of combined rounding error, so 0.02 is within reach.
   Fix: re-foot from unrounded source amounts; if the variance clears, record the rounding and close the item.

4. **Scope limit.** This check covers only the nine lines provided. Any spend outside them is not tested.
   Fix: if the header is meant to be the full-day total, confirm no company spend line sits outside the COMPANY DATA set.
