# Auditor: Verify spend footing line by line against today s feed

Date: 2026-11-13
Task: Verify spend footing line by line against today's feed
For [[Steward]].

## Spend Footing Audit: Findings

**Result: footing is not verified.** The feed cuts off after "Fe," so no stated total or currency appears, and the lines I can see cannot be checked against a total.

**Visible line sum: 5.58** (0.54 + 4.06 + 0.17 + 0.27 + 0.01 + 0.33 + 0.16 + 0.03 + 0.01)

Ranked by impact:

1. **Feed is truncated, so there is nothing to foot against.** The total line and any trailing lines are missing. *Fix:* re-pull the full feed and reject sign-off until the stated total matches the sum of all lines.

2. **Minion lines may double count.** If bard-minions, herald-minions, and steward-minions roll up into their parent desks, the parents alone sum to 5.38 and the minions add 0.20. Summing everything gives 5.58, which overstates spend by 0.20 in that case. *Fix:* confirm whether minion lines are separate ledger entries or rollups, and state that in the feed header.

3. **Corvid concentration.** Corvid is 4.06 of 5.58 visible spend (about 73%), so any error or runaway job there dominates the total. *Fix:* break corvid's line into job or task IDs so a single outlier is visible at a glance.

4. **Currency and window are unlabeled.** The lines have no currency, period, or timezone. *Fix:* add "USD, today, UTC" (or the actual values) to the feed header so the footing is auditable.

5. **Rounding tolerance is undefined.** Two-decimal lines can drift from the true total by a few cents. *Fix:* state the tolerance (for example, plus or minus 0.05 across nine lines) and flag anything outside it.

6. **Spend is not linked to a revenue metric.** Nothing here shows what the spend produced. *Fix:* if no revenue-per-desk number exists, log "not instrumented yet" and file a job to attach Korvus signups or Eclipse-X joins to each desk's spend line.

**Next step:** Steward should re-request the complete feed with the total line. Footing can be signed off once items 1 and 2 are resolved.
