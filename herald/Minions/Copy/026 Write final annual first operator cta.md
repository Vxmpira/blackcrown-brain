# Copy: Write final annual first operator cta set with exact wording

Date: 2026-10-26
Task: Write final annual-first Operator CTA set with exact wording
For [[Herald]].

**Operator Annual CTA Set**
*Moves the Operator MRR rung. Annual is listed first in every surface.*

**Variant A: Direct**

- **Body:** Korvus watches index futures around the clock so you don't have to. Operator is 79.99 a year, or 9.99 a month. Annual saves you 39.89 against twelve monthly payments. LodeStone TradingView access is included.
- **Button:** Get Operator annual
- **Button link:** Operator annual checkout, standard Korvus UTM tagging
- **Disclaimer:** Korvus is market intelligence and education, not financial advice. Trading index futures involves substantial risk of loss. Past readings do not predict results.

**Variant B: Operator to operator**

- **Body:** You already watch the open. Korvus watches it with you, 24/7, while you sleep. Operator is 79.99 a year, which is 39.89 less than paying 9.99 a month. LodeStone for TradingView comes with it.
- **Button:** Start Operator for 79.99 a year
- **Button link:** Operator annual checkout, standard Korvus UTM tagging
- **Disclaimer:** Korvus is market intelligence and education, not financial advice. Trading index futures involves substantial risk of loss. Past readings do not predict results.

**Button check:** Variant A's button is 3 words. Variant B's is 7 words, which breaks the under-6 rule. Use this shorter fix for B: **Start Operator annual** (3 words). Use it in place of the longer button wherever B runs.

**Compliance:** No em dashes, no emoji, no obligation wording. No "risk free," "cancel anytime," or "free trial" language appears.

**Overclaim flags, review before shipping:**

1. **"Watches index futures around the clock" and "24/7":** Accurate to the product description, but it describes coverage, not results. Do not extend it into "catches every move" or "never misses" phrasing.
2. **"Watches it with you" (Variant B):** Keep it framed as monitoring. It must not suggest Korvus makes trading decisions or signals entries.
3. **"Annual saves you 39.89":** Verified math: 9.99 × 12 = 119.88, minus 79.99 = 39.89. Safe as long as both prices stay current in Stripe. If the monthly price changes, this figure must be recomputed before it runs again.
4. **"LodeStone TradingView access is included":** Accurate for Operator. Do not describe LodeStone as a feature that improves results or as a signal source. It is a session level toolkit.
5. **Placement risk on korvus_landing:** The landing page injects prices server side from Stripe display tokens and must never hardcode dollar amounts. These figures are approved for ad, email, and social channels. If this copy goes onto the landing page itself, the prices must come from the token injection, not from this text.
6. **Motto risk:** "Your edge while the world sleeps" is a house motto and is deliberately absent here. It reads as a performance promise. Keep it out of CTAs.
