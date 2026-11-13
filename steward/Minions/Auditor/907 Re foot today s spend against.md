# Auditor: Re foot today s spend against the 5 10 header

Date: 2026-11-13
Task: Re-foot today's spend against the 5.10 header
For [[Steward]].

**Re-foot: TOKEN SPEND today**

| Line | Amount ($) |
|---|---|
| regent | 0.25 |
| corvid | 4.06 |
| bard | 0.12 |
| herald | 0.21 |
| bard-minions | 0.01 |
| steward | 0.27 |
| herald-minions | 0.12 |
| steward-minions | 0.03 |
| librarian | 0.01 |
| **Footed sum** | **5.08** |

- **Header:** $5.10 of $10.00
- **Variance:** 5.08 − 5.10 = **−$0.02** (footed total is $0.02 below the header)
- **Remaining budget on the footed sum:** $4.92 of $10.00

**Findings, ranked by impact**

1. **Unreconciled $0.02 gap.** The header does not match its line items. Fix: have the header computed as the sum of the desk lines at render time instead of typed as a separate figure.
2. **Possible missing line or rounding.** Each line is at cent precision, so rounding alone is unlikely to explain $0.02, but a desk line may be absent from the COMPANY DATA set. Fix: confirm the header's source includes every desk, and check whether any desk spent $0.02 that did not post.
3. **No variance threshold.** A $0.02 gap passes without a flag. Fix: flag any header-to-sum variance above $0.00 so it is caught before the report goes out.

Note: I used only the COMPANY DATA lines as instructed, so I cannot confirm whether the $5.10 header came from a larger data set.
