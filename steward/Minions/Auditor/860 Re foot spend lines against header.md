# Auditor: Re foot spend lines against header with unrounded values

Date: 2026-11-12
Task: Re-foot spend lines against header with unrounded values
For [[Steward]].

**Re-foot result: does not tie at the cent. Cause not determinable from the feed.**

Recomputed line sum from the rounded figures: **9.66**. Header: **9.67**. Gap: **0.01**.

**Findings, ranked by impact**

1. **Unrounded values are not in the feed.** The task asks for a re-foot on unrounded values, but the feed carries only cent-rounded lines. Nothing here can prove which line holds the residual, so no holder can be named.
   *Fix:* Pull the unrounded per-desk spend from the metering ledger and re-foot against it.

2. **The gap is consistent with normal rounding.** Eleven lines each rounded to the cent can drift up to 0.055 in total (11 × 0.005). A 0.01 residual is well inside that band, so the header may be the rounded sum of unrounded lines, which is expected.
   *Fix:* Confirm the header is computed as round(sum of unrounded lines). If so, log it as a rounding residual and make no correction.

3. **Zero-display line may hide sub-cent spend.** The minions line shows 0.00 and could carry a fraction of a cent that is rounded away.
   *Fix:* Show three decimals on the spend feed so sub-cent lines stay visible.

4. **Header and lines use different precision.** A header built from one precision and lines shown at another will keep producing gaps like this one.
   *Fix:* Render header and all lines from the same unrounded source with one rounding step at display time.

**Disposition:** No match is written. The 0.01 gap stays open until the unrounded ledger is pulled (finding 1). If the unrounded lines sum to the header, close as rounding. If they do not, the discrepancy is real and goes to the owner.
