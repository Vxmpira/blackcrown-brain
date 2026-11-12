# Auditor: Gate the exact text of the complete lodestone value post

Date: 2026-11-11
Task: Gate the exact text of the complete LodeStone value post, one reconciled verdict quoting the exact string
For [[Steward]].

**Verdict: PASS for content. Conditional FAIL if routed to X.**

**Content gate: PASS. No failing string.**

- **Pricing:** "$149 one time" (Tradovate) and "$19.99 a month" (TradingView) match the LodeStone ground truth. The 19.99 is correct and is not flagged.
- **Delivery and checkout:** "delivered as a code file to your checkout email" matches the Tradovate fulfillment described in memory.
- **Buy location:** "Buy buttons are in #korvus-indicator" is accurate.
- **Disclaimer:** The full not-advice block is present: "Not financial advice," educational tool, no predictions or guarantees, and the substantial risk of loss warning for index futures.
- **Prohibited content:** No profit promises, no trading advice, no emoji, no em dashes, no hype.
- **Minor note, not a fail:** "where price reacts to them" describes behavior and does not predict it. Keep it as written.

**Channel gate: conditional.**

The text runs roughly 600 characters. X posts are capped at 280 characters, with links counting 23 each. If Herald or Crier routes this to X, it fails preflight on length. If it is for Discord, a blog, or another long-form surface, it passes.

**Fix if X is the target:** Cut to the hook and one price line, keep the disclaimer on the product claim, and cap at two hashtags. Alternatively, file the long version as the Discord or site copy and cut a separate X version.
