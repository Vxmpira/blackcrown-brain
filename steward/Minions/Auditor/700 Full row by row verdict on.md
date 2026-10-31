# Auditor: Full row by row verdict on overnight text final verdict

Date: 2026-10-31
Task: Full row-by-row verdict on overnight text, final verdict line required
For [[Steward]].

## Row-by-row check

| # | Check | Result | Evidence |
|---|---|---|---|
| 1 | Em dashes | Pass | None in the text. |
| 2 | Emoji | Pass | None in the text. |
| 3 | Not-advice line | Pass | "Not financial advice." closes the text. |
| 4 | Profit or performance claims | Pass | No returns, edge, accuracy, or win-rate language. |
| 5 | Trading signal framing | Pass | "Tracking, not a signal." explicitly disclaims signal status. "Review the news flow" is observational. |
| 6 | Product description matches Korvus record | Pass | Scored headlines with impact, direction, and confidence matches the Korvus wire scoring in the record. No feature is overstated. |
| 7 | Length for Discord | Pass | About 60 words, four short sentences, no wall of text. |
| 8 | Voice and standards | Pass | Operator-to-operator, no hype, no guru framing. |
| 9 | Market claim hedging | Pass | "Often set the tone" is hedged and makes no predictive promise. |
| 10 | Link and UTM | Not applicable | The text has no Korvus link. If one is added, it must carry the standing UTM tags. |
| 11 | Truncation | Pass | Judged in full, no rows skipped. |

## Findings, ranked by impact

1. **Direction wording sits close to signal language.** Low risk, because the disclaimer follows immediately. Fix: change "scored headlines with impact, direction, and confidence" to "scored headlines with impact, direction, and confidence scores" to make the scoring read as description, not a call.
2. **A future link would need UTM tags.** This is a conditional risk only. Fix: when a korvus.industries link is added, apply the standing UTM tagging and do not refile it.

No blocking issues found.

FINAL VERDICT: PASS
