# Pitch: Draft one page click test budget sizing for owner

Date: 2026-11-13
Task: Draft one-page click test budget sizing for owner
For [[Herald]].

# Click Test Budget Sizing: Draft for Owner

**Status:** Draft for Regent review. Nothing is approved or spent. Owner green light in #boardroom is required before any spend.
**Serves rung:** First paying customer (Korvus signups, Herald quota of 50 signups).

## 1. What the test needs

| Item | Value |
|---|---|
| Human visits per variant | 300 |
| Variants | 2 |
| Total human visits needed | 600 |
| Test window | 14 days |
| Visits needed per day | about 43 (600 / 14 = 42.9) |

## 2. Where traffic stands today

| Measure | Visits |
|---|---|
| Today (partial day, as of filing) | 5 |
| Last 7 days, total | 93 |
| Last 7 days, daily average | about 13.3 |

Caveat: the 93 is not yet verified as human only. Bot and internal traffic filtering is not instrumented yet.

## 3. The visit gap

| Measure | Value |
|---|---|
| Daily gap (43 needed minus 13.3 current) | about 30 visits per day |
| 14-day need | 600 visits |
| 14-day baseline if current pace holds (13.3 x 14) | about 186 visits |
| 14-day gap the paid traffic must cover | about 414 visits |

Assumption: the baseline visits are not counted toward the test. If some of them do land on the test pages, the gap shrinks by that amount.

## 4. Cost, owner fills in

Cost per visit is **not instrumented yet**. The range below is a formula, not an estimate.

**Formula:** Gap visits (414) x cost per visit = test media budget

| Cost per visit (owner enters) | Test media budget (414 visits) |
|---|---|
| $ [____] low | $ [____] |
| $ [____] mid | $ [____] |
| $ [____] high | $ [____] |

No cost-per-visit figure appears here because none is measured yet. Fill the range from your own platform quotes.

## 5. What is instrumented and what is not

- **Instrumented:** Visit counts per page. UTM tagging on outbound Korvus links has been live since 2026-10-26 and covers source attribution.
- **Not instrumented yet:** Spend per visit by source, human-only visit filtering, and signup conversion per variant.
- **Proposed job:** File an instrumentation job to pull spend per source and join it to UTM visit counts, so the cost table in section 4 fills itself. Needs owner approval before filing.

## 6. Decision for the owner

1. Enter a cost-per-visit range in section 4.
2. Pick a total test budget from that range, or hold.
3. Green light the instrumentation job in section 5 so the next sizing run has real numbers.

Any Korvus product claim in the test copy keeps the not-advice disclaimer. This document makes no profit or return claims.
