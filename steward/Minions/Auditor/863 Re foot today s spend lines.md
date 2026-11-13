# Auditor: Re foot today s spend lines against header

Date: 2026-11-13
Task: Re-foot today's spend lines against header
For [[Steward]].

**Re-foot result: lines sum to 0.73, header reads 0.74. Gap of 0.01 (header higher).**

Line check: 0.07 + 0.63 + 0.01 + 0.01 + 0.00 + 0.01 + 0.00 + 0.00 = 0.73

Budget use: 0.73 of 10.00 is 7.3%. The header implies 7.4%.

**Findings, ranked by impact**

1. **Unreconciled 0.01 between header and lines.** The difference is small but unexplained, and the header is the number the owner sees. Likely cause is per-line rounding to cents, since eight rounded lines can drift up to about 0.04 from the true total. Fix: pull unrounded line totals from the cost source and re-foot to the tenth of a cent, or add a rounding note to the header.

2. **Corvid is 86% of today's spend (0.63 of 0.73).** This is the largest single cost concentration. Fix: tag Corvid's 0.63 to the specific job or ask that drove it, so the owner can tell whether that spend produced a revenue move.

3. **Three lines show 0.00 (bard-minions, herald-minions, steward-minions).** A zero may mean the minions did no work, or that their cost is not instrumented and is being rounded away. Fix: confirm whether these desks ran today; if they did, instrument their cost so it stops hiding below the rounding floor.

4. **Spend is a small share of budget (7.3%), so there is no immediate pressure.** The risk is in reporting, not in the total. Fix: keep the daily re-foot in the Steward report with unrounded figures so future gaps do not recur silently.
