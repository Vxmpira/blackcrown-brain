# Auditor: Re foot spend on the full ten line feed

Date: 2026-11-13
Task: Re-foot spend on the full ten-line feed
For [[Steward]].

## Spend Re-foot: Full Ten-Line Feed

| Item | Value |
|---|---|
| Line sum (10 lines) | **8.12** |
| Header | **8.14** |
| Gap (header minus sum) | **0.02** |

The ten lines add to 8.12. The header reads 8.14, so the header is 0.02 higher than the lines support. The 6.82 and 7.35 figures were not used.

## Auditor Findings

1. **Unreconciled 0.02 gap (medium).** The header overstates the line items by 0.02. The likely causes are rounding at the line level or a spend source missing from the roll-up. **Fix:** have the header computed as the sum of the ten lines, and log the 0.02 until its source is identified.

2. **Corvid concentration (medium).** Corvid is 4.48 of 8.12, about 55% of total spend. Revenue per desk is not instrumented yet, so the spend cannot be checked against output. **Fix:** file a job that ties each desk's spend to its revenue-aimed output so Corvid's share can be justified or cut.

3. **Minion spend is small but untracked against owners (low).** Bard-minions 0.04, herald-minions 0.17, and steward-minions 0.04 sum to 0.25. Each sits under its parent desk with no separate accountability. **Fix:** tag minion lines to a named parent in the feed so the parent's total is auditable without manual addition.
