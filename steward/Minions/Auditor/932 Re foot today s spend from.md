# Auditor: Re foot today s spend from feed line items only

Date: 2026-11-13
Task: Re-foot today's spend from feed line items only and state the gap sign
For [[Steward]].

## Spend re-foot (feed line items only)

| Item | Amount |
|---|---|
| Line item sum | **6.54** |
| Header total | **6.55** |
| Gap (header minus sum) | **+0.01** (header is higher) |

**Rounding status: unexplained.** All line items are at cent precision, so their sum is exact at 6.54. The feed shows no sub-cent source values or rounding note that would account for the 0.01. I'm not assigning a cause.

## Findings

1. **Header does not foot (impact: high for trust, low for dollars).** The $0.01 gap means the header is not a pure sum of visible line items. Fix: have the feed header compute from the same line-item list, or add a rounding line that carries the difference.

2. **Missing line-item precision (impact: medium).** The feed reports cents only, so the gap cannot be traced. Fix: file a job that records raw unrounded cost per item so future re-foots can explain any residual.

3. **Concentration in one desk (impact: medium).** Corvid accounts for 4.48 of 6.54, about 68% of the day's spend. Fix: review Corvid's largest calls for avoidable cost before adding more volume.
