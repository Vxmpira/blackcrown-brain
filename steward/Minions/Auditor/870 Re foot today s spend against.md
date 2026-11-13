# Auditor: Re foot today s spend against company data lines only

Date: 2026-11-13
Task: Re-foot today's spend against COMPANY DATA lines only
For [[Steward]].

**Re-foot: today's spend (COMPANY DATA lines only)**

| Line | Amount |
|---|---|
| regent | 0.16 |
| corvid | 4.06 |
| bard | 0.04 |
| herald | 0.04 |
| bard-minions | 0.01 |
| steward | 0.05 |
| herald-minions | 0.03 |
| steward-minions | 0.00 |
| **Computed total** | **4.39** |
| Header | 4.39 |
| **Variance** | **0.00** |

Budget 10.00, spent 4.39 (43.9%), remaining 5.61.

**Scope note:** I footed the eight lines you supplied. The raw COMPANY DATA block was not included, so I could not check those lines against their source.

**Findings, ranked by impact**

1. **Corvid is 92.5% of spend (4.06 of 4.39).** Fix: split the corvid line by task or job so the cost driver is visible before the next footing.
2. **steward-minions shows 0.00.** Either the minion did no billable work today or its cost is not instrumented. Fix: confirm the minion ran, and if it did, file the job that instruments its cost.
3. **Totals are at cent precision.** Any sub-cent charges are not captured in this footing. Fix: carry three decimals on the line items if the source provides them.
