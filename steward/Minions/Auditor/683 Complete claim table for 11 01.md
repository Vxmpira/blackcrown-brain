# Auditor: Complete claim table for 11 01 observer post then audit

Date: 2026-10-30
Task: Complete claim table for 11-01 Observer post, then audit 10-31 fallback.
For [[Steward]].

## 11-01 Observer post: claims 6 onward

I received claims 1 to 5 as already passing but not their full wording, so I enumerated the remaining checkable claims from the post text.

| # | Claim | Source text | Check against memory | Verdict |
|---|---|---|---|---|
| 6 | Link points to the Korvus domain | korvus.industries | Matches the public Korvus landing | PASS |
| 7 | #futures tag fits the subject | #futures | Post is about index futures | PASS |
| 8 | #daytrading tag fits the audience | #daytrading | Index futures traders are the stated audience | PASS |
| 9 | Hashtag count within the two-tag cap | 2 tags | Cap is two | PASS |
| 10 | No card claim present | Text says nothing about a card | Memory grants no-card only to Crown's free tier, not Observer. Absence is correct | PASS |
| 11 | No em dashes or emoji | None found | House rule | PASS |
| 12 | No profit promise or trading advice | "Can move on a headline" describes volatility, not outcomes | Brand rule | PASS |
| 13 | Not-advice disclaimer present | "Not financial advice." | Required on product claims | PASS |
| 14 | Under the 280 character limit | About 235 characters, link counted at 23 | X limit | PASS |

**11-01 verdict: PASS. Clear to ship.**

## 10-31 fallback: full audit

| # | Claim | Source text | Check against memory | Verdict |
|---|---|---|---|---|
| A | Futures do not stop at 4pm | "Index futures don't stop at 4pm." | Index futures trade on Globex nearly around the clock, with a daily maintenance break. The 4pm reference is the cash equity close, so the statement holds | PASS |
| B | Overnight and Asia sessions move levels | "Overnight sessions and the Asia open keep moving levels while you sleep." | Qualitative market behavior, no numbers, no advice | PASS |
| C | Korvus is a 24/7 terminal for reviewing changes | "Korvus runs a 24/7 market intelligence terminal so you can review what changed." | Matches the Korvus description | PASS |
| D | Free tier exists | "Free tier available." | Observer is free | PASS |
| E | Not-advice disclaimer present | "Not financial advice." | Required | PASS |
| F | Link resolves to Korvus | https://korvus.industries | Public landing | PASS |
| G | #NQ fits the subject | #NQ | Nasdaq index futures, on topic | PASS |
| H | Hashtag count within cap | 1 tag | Cap is two | PASS |
| I | No card claim present | Absent | Correct, Observer has no card claim in memory | PASS |
| J | No em dashes or emoji | None found | House rule | PASS |

**10-31 verdict: PASS with one wording fix.**

## Ranked findings

1. **Tier naming drifts between posts.** 10-31 says "Free tier," while the Observer post says "Observer tier." Fix: change "Free tier available" to "Observer tier is free" so both posts use the product name.
2. **Overnight claim is unquantified.** Claim B is accurate but vague. Fix: optional, keep as is or change "keep moving levels" to "can move levels" for a more defensible read.

Neither finding blocks shipping. Both posts are clear, and neither adds a card claim.
