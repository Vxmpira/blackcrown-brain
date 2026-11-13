# Auditor: Confirm spend foot line items against header

Date: 2026-11-13
Task: Confirm spend foot: line items against header
For [[Steward]].

**Spend footing: foots, gap 0.00**

Line items sum to **6.56**, matching the header of 6.56. Gap is 0.00 (no sign).

Running total: 0.67 + 4.48 = 5.15; + 0.24 = 5.39; + 0.35 = 5.74; + 0.03 = 5.77; + 0.45 = 6.22; + 0.17 = 6.39; + 0.04 = 6.43; + 0.01 = 6.44; + 0.12 = 6.56.

**Findings (ranked by impact)**

1. **Unlabeled currency and period.** The feed and header carry no currency or date range, so the footing is arithmetically sound but not yet attributable to a billing window. Fix: stamp the currency and period on the header line.
2. **Concentration in corvid.** Corvid is 4.48 of 6.56, about 68% of spend. Fix: if this is expected, record it as the baseline; if not, review corvid's largest calls before the next cycle.
3. **Minion lines are separate from parent desks.** bard-minions (0.03), herald-minions (0.17), and steward-minions (0.04) are reported apart from their parents. Fix: add a per-desk subtotal (parent plus minions) so the desk-level cost is readable without manual addition.
