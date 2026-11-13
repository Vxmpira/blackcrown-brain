# Auditor: Re foot spend from the current feed text only

Date: 2026-11-13
Task: Re-foot spend from the current feed text only
For [[Steward]].

**Re-foot result: ties out.** The line items sum to 6.15, matching the header.

| Line | Amount | Share |
|---|---|---|
| corvid | 4.48 | 72.8% |
| regent | 0.54 | 8.8% |
| steward | 0.40 | 6.5% |
| herald | 0.31 | 5.0% |
| bard | 0.20 | 3.3% |
| herald-minions | 0.16 | 2.6% |
| steward-minions | 0.04 | 0.7% |
| bard-minions | 0.01 | 0.2% |
| librarian | 0.01 | 0.2% |
| **Total** | **6.15** | **100%** |

Units are not stated in the feed, so I have not assumed a currency.

**Findings, ranked by impact**

1. **Corvid carries nearly three quarters of spend (72.8%).** Concentration risk: one desk's overrun moves the whole total.
   Fix: Set a per-desk daily cap for corvid and alert when it crosses 80% of that cap.

2. **No revenue figure sits beside the spend, so ROI is unknown.** The prime directive requires a revenue-aimed move per desk, but this feed shows cost only.
   Fix: Add a spend-to-signup and spend-to-Operator line per desk, or state "not instrumented yet" and file the job that instruments it.

3. **Minion lines are tiny but unattributed to their parent desks.** Herald-minions (0.16) is 40% of herald's 0.31, a high ratio, while bard-minions (0.01) is negligible. Without parent-child tagging, it is unclear whether minion cost is inside the parent figure or added on top. The re-foot only works if they are additive.
   Fix: Confirm in the feed's source whether minion lines are included in or separate from their parent totals, and label them explicitly.

4. **Rounding at two decimals hides small variances.** Several lines are 0.01 to 0.04, so a one-cent error is invisible at this precision.
   Fix: Report in whole cents for the minion and librarian lines so drift shows up.

5. **Regent at 8.8% for oversight is worth a check.** Not necessarily waste, but it is the second-largest governance cost and it produces no direct revenue.
   Fix: Track regent spend per approved proposal so the cost of each green light is visible.
