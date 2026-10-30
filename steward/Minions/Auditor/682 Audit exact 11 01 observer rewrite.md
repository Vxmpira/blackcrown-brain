# Auditor: Audit exact 11 01 observer rewrite full claim table

Date: 2026-10-30
Task: Audit exact 11-01 Observer rewrite, full claim table
For [[Steward]].

# Audit: 11-01 Observer rewrite (exact text)

**No-card claim: ABSENT.** The text contains no "card," "no card required," or equivalent wording.

## Claim table

| # | Claim | Verdict | Basis |
|---|---|---|---|
| 1 | "Index futures can move on a headline in seconds." | PASS | General market observation. No outcome or profit promise. |
| 2 | "Korvus runs a 24/7 market intelligence terminal" | PASS | Matches ground truth: 24/7 market intelligence terminal. |
| 3 | "the Observer tier is free" | PASS | Observer is the free Korvus tier. |
| 4 | "Not financial advice." | PASS | Required disclaimer on product claims is present. |
| 5 | "Built to watch the market while you sleep." | PASS | Consistent with the 24/7 watcher angle and the "edge while the world sleeps" motto. |
| 6 | "korvus.industries" | PASS | Correct domain. Attribution depends on the standing UTM infrastructure, not the bare text. |
| 7 | Two hashtags (#futures #daytrading) | PASS | Within the two-hashtag maximum. |
| 8 | No em dashes, no emoji | PASS | None present. |
| 9 | No-card claim | ABSENT | Not in this text, so nothing to ground or fail. |
| 10 | Length limit (280) | PASS | My count is 238 with the link at 23. The stated 239 is off by one. Harmless, but correct the figure in the record. |
| 11 | No profit promise, no trading advice | PASS | No directional call, no return language. |

## Findings, ranked by impact

1. **No blocking issues.** All eleven checks pass on the exact text. The post is ready to file on the standing X path.
2. **Character count record is off by one.** Correct the stated 239 to 238 so the audit trail matches the text.
3. **Conversion is not instrumented past the click.** Observer is free, so the post correctly stops at the top of the funnel. Fix: confirm the UTM tag on this link lands in analytics, or mark signup attribution as "not instrumented yet" in the report.
