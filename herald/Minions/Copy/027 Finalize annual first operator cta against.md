# Copy: Finalize annual first operator cta against live wording

Date: 2026-10-26
Task: Finalize annual-first Operator CTA against live wording
For [[Herald]].

**Status: blocked on live text.** Corvid has not returned the live Korvus hero and Operator CTA wording, so I can't score against it yet. The candidate below is built to the locked constraints. Re-score it once Corvid's block arrives.

**Candidate CTA copy**

Headline: Operator. Annual first.

Plan block, annual listed first:
- **Operator Annual: 79.99 a year.** Saves 39.89 against twelve months of Operator Monthly. Includes the LodeStone TradingView indicator.
- Operator Monthly: 9.99 a month. Includes the LodeStone TradingView indicator.

Button: Start Operator Annual

Supporting line: 24/7 market intelligence for index futures traders, with the LodeStone chart toolkit included.

Fine print: Korvus provides market information and education tools. It is not financial advice, and it does not recommend trades. Trading involves risk of loss, and nothing here promises results.

**Link placeholder (UTM already standing infrastructure, do not refile)**

`https://korvus.industries/signup?plan=annual&utm_source=[SOURCE]&utm_medium=[MEDIUM]&utm_campaign=[CAMPAIGN]`

Fill the bracketed tags with the existing UTM scheme. The shipped tagging on outbound Korvus links is not reproduced here, so do not invent new parameter names.

**Math check**
- 9.99 x 12 = 119.88
- 119.88 - 79.99 = 39.89 saved. Correct.

**Honesty rubric self-score (candidate only)**
- No profit claims, no performance promises: pass
- No trading advice or trade direction: pass
- Not-financial-advice line present: pass
- LodeStone inclusion stated accurately (included with Operator): pass
- Annual listed first with computed savings: pass
- No em dashes, no emoji: pass
- Live wording alignment: not yet scored

**Two things to resolve before this files**
1. **Dollar amounts:** korvus_landing prices inject server side from Stripe display tokens, and dollar amounts must never be hardcoded on that page. Any proposal changing the CTA must route 79.99, 9.99, and 39.89 through the token injection, not literal text. Corvid's live block should show how the injection points are currently wired.
2. **Filing target:** this is an edit to the Korvus landing page (korvus:korvus_landing.html), which is a section of that file, not a new page. The proposal needs exact CURRENT anchors copied from the live file. No new page is needed, so no FROM NOTE path applies.

Next step: request Corvid's live hero and CTA text, then I'll finalize the exact wording and file the proposal for Regent review.
