# Auditor: Audit the 11 01 observer rewrite with a complete claim

Date: 2026-10-30
Task: Audit the 11-01 Observer rewrite with a complete claim table, PASS or FAIL
For [[Steward]].

## Audit: 11-01 Observer rewrite

**Overall verdict: FAIL (1 claim fails, 1 check needs confirmation before filing)**

Length check: 263 characters with the link counted at 23. Under the 280 limit.

### Claim table

| # | Claim (verbatim) | Verdict | Basis |
|---|---|---|---|
| 1 | "Index futures can move on headlines within seconds." | PASS | General market observation, not a profit promise or trading advice. |
| 2 | "Korvus runs a 24/7 market intelligence terminal" | PASS | Matches ground truth: 24/7 market intelligence terminal for index futures traders. |
| 3 | "and the Observer tier is free" | PASS | Observer is the free Korvus tier. |
| 4 | "with no card required" | FAIL | Ground truth states Observer is free but says nothing about card requirements. The card-free claim is only documented for Crown's free tier. Unverified claims in paid-facing copy are not allowed. |
| 5 | "Not financial advice." | PASS | Not-advice disclaimer is present, as required on product claims. |
| 6 | "Built to watch the market while you sleep." | PASS | Consistent with the 24/7 watcher angle and the "Your edge while the world sleeps" motto. Makes no performance claim. |
| 7 | "korvus.industries" | PASS | Correct domain. Counts as 23 characters. Outbound UTM tagging is standing infrastructure and must not be refiled. |
| 8 | "#futures #daytrading" | PASS | Two hashtags, within the maximum. |
| 9 | No em dashes, no emoji | PASS | None present. |
| 10 | No dollar amounts or price figures | PASS | Complies with the pricing rule (prices are never hardcoded in copy). |
| 11 | No Presidential Wire scoring claim | PASS | Removed, per the prior failure. |
| 12 | No "most traders" audience claim | PASS | Removed, per the prior failure. |
| 13 | No profit, win-rate, or guaranteed-outcome language | PASS | None present. |
| 14 | Length within 280 characters | PASS | 263 characters with link at 23. |
| 15 | Platform is wired (X, direct from server) | PASS | X posts direct from the server with brand keys. |
| 16 | Voice: operator to operator, no hype | PASS | Plain statements, no guru framing. |

### Findings, ranked by impact

1. **Row 4, "with no card required" (FAIL).** This is an unverified claim about signup friction on the main funnel. If it's false, it burns trust with the skeptics the brand is trying to win.
   - **Fix:** Verify the Observer signup flow requires no card and confirm it with the owner, or cut the clause. The sentence still works as "and the Observer tier is free."

2. **Row 7, UTM tagging (check).** The text links the bare domain, so UTM tagging depends on the posting pipeline applying it automatically.
   - **Fix:** Confirm the X posting path appends the standing UTM parameters to the link. Do not refile the UTM work.

3. **Row 1, unsourced market statement (low risk).** The "move within seconds" line is generic and true in spirit, but it carries no source.
   - **Fix:** Optional. Keep as is, since it makes no quantitative claim.

**Filing recommendation:** Do not file until Finding 1 is resolved. If the card claim is cut, the post passes all remaining checks.
