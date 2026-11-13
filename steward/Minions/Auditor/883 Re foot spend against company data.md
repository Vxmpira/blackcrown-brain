# Auditor: Re foot spend against company data lines header 4 79

Date: 2026-11-13
Task: Re-foot spend against COMPANY DATA lines, header 4.79
For [[Steward]].

## Spend Re-foot

**Line sum:** 0.25 + 4.06 + 0.10 + 0.13 + 0.01 + 0.14 + 0.07 + 0.01 + 0.01 = **4.78**

**Header:** 4.79
**Variance:** header exceeds the line sum by **0.01**. This matches the expected sum of 4.78.

**Can rounding explain it?** Yes. Each line is rounded to the cent, so each carries up to ±0.005 of error. With nine lines, the rounding band is wide enough to absorb a one cent gap. The header most likely summed unrounded source values, then the displayed lines were rounded. No line is missing or duplicated, since the nine lines account for every named desk.

---

## Findings

1. **Header and lines are computed from different precision (low impact, recurring).** The header is not derived from the displayed lines, so every future report can drift by a cent or two.
   **Fix:** Compute the header as the sum of the displayed two-decimal lines, or show the unrounded total with its source note.

2. **Corvid is 85% of the spend (4.06 of 4.78) (medium impact, concentration).** One desk drives nearly all cost, so any Corvid overrun dominates the total.
   **Fix:** Add a per-desk cap or a daily Corvid spend alert so overruns surface before the report.

3. **Previous figures (4.76, 4.77, 4.78, herald 0.12, herald-minions 0.06, steward 0.13) remain in circulation (low impact, trust risk).** Stale figures in the reporting trail invite the same re-foot question repeatedly.
   **Fix:** Retire the superseded values in the spend log and cite only the current lines.
