# Auditor: Issue one reconciled verdict quoting the exact lodestone post string

Date: 2026-11-11
Task: Issue one reconciled verdict quoting the exact LodeStone post string
For [[Steward]].

## Verdict: Not issued. The post string and both prior reports are missing.

I can't quote the LodeStone post or reconcile the two reports without them. Quoting from memory would be fabrication. Please send:

1. The exact LodeStone post text, unedited.
2. Report A (the conditional FAIL for X routing).
3. Report B (the PASS with the advisory revision).

## Reconciliation logic, applied once I have the text

- **The X failure does not carry over.** Report A's failure is conditioned on X routing. Steward scoped this task to Eclipse-X Discord only, so that condition does not fire. Discord has no 280-character limit, no link-weight rule, and no two-hashtag cap.
- **Report B's PASS is not actionable as written.** "Advisory revision, unspecified" fails the filing standard: every change must state exactly what it triggers. Either the revision is named exactly or the PASS is withdrawn.
- **Result:** If the post passes the Discord checks below, the verdict is PASS with a named revision, or a clean PASS if no revision is needed. If it fails any check, the verdict is FAIL with the exact string quoted.

## Checks the Discord post must pass

Ranked by impact:

1. **LodeStone price accuracy (blocker).** Any price must match a real product. Tradovate version: $149 one time, delivered as a code file to checkout email. TradingView version: $19.99 a month. Never call the $19.99 a mistake, and never confuse the two.
   *Fix:* Name the product next to every price.
2. **No advice or profit promises (blocker).** No profit claims, no "will make," no trade calls.
   *Fix:* Strike any outcome language and keep the not-advice disclaimer on product claims.
3. **No em dashes, no emoji (blocker).** Applies to all outbound copy.
   *Fix:* Replace each em dash with a comma, colon, or period.
4. **Value first, no hype, no begging (high).** Community posts must be specific to the trading tools.
   *Fix:* Lead with a concrete feature (session levels, prior day and week levels, SMT divergence) and cut superlatives.
5. **Correct channel reference (medium).** Buy buttons live in #korvus-indicator. Point there, not to a generic link.
   *Fix:* Replace any generic purchase link with a pointer to #korvus-indicator.

Send the three items and I'll issue the single verdict with the quoted passing and failing strings.
