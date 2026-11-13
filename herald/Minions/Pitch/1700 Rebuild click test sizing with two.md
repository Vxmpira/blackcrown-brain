# Pitch: Rebuild click test sizing with two funded options

Date: 2026-11-13
Task: Rebuild click test sizing with two funded options
For [[Herald]].

# Click Test Sizing: Two Funded Options

**Status: no spend approved. Owner decision required.**
**Denominator caveat: the human-only visit count is not yet returned.** The 93 organic visits are unverified and may include bots, so the true gap could be larger than shown here.

## Target
- 300 human visits per variant, 600 total
- 14-day window needs about 43 human visits/day
- Organic baseline: about 13/day (93 over 7 days, unverified), plus 5 partial today

## Option A: Paid traffic, hold the 14-day window
Paid traffic covers the gap between 43/day and organic 13/day, about 30/day.

| Item | Math | Result |
|---|---|---|
| Organic over 14 days | 13 × 14 | 182 visits |
| Paid visits needed | 600 − 182 | 418 visits |
| Add 20% buffer for invalid or low-quality clicks | 418 × 1.2 | ~502 paid clicks |
| Cost at $0.50 per click (illustrative) | 502 × $0.50 | ~$251 |
| Cost at $1.00 per click (illustrative) | 502 × $1.00 | ~$502 |
| Cost at $1.50 per click (illustrative) | 502 × $1.50 | ~$753 |

CPC is an illustrative assumption. Real click cost is not instrumented yet. A test run will establish it.

**Tradeoff:** fastest read, but spend is required and the buffer may be too small if bot share is high.

## Option B: Organic only, extend the window
No spend. The window stretches to meet the target at the current organic rate.

| Item | Math | Result |
|---|---|---|
| Days needed at 13/day | 600 ÷ 13 | 46.2, so plan for 47 days |
| Spend | none | $0 |

**Tradeoff:** zero cost, but the read arrives more than three times later. Organic volume is unverified, so the 47-day estimate may be optimistic.

## Recommended sequencing
1. Return the human-only denominator before either option is funded. It determines whether the gap is 30/day or larger.
2. If the owner wants a faster read, Option A with a capped test budget is the only path to 14 days.
3. If speed is not urgent, Option B costs nothing and can start immediately.

Korvus is market intelligence for index futures traders. It is not financial advice, and nothing in this test promises trading results.
