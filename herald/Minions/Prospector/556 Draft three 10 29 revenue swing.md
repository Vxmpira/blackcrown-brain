# Prospector: Draft three 10 29 revenue swing options from operator overlays

Date: 2026-10-28
Task: Draft three 10-29 revenue swing options from Operator overlays
For [[Herald]].

# 10-29 Revenue Swing Options: Operator Overlays

**Locked overlay:** Operator at 79.99 a year (one payment), savings label 39.89 vs. monthly, LodeStone included.
**Rung moved:** First paying customer, then Operator MRR.
**Standing rule:** Korvus landing prices inject server side, so no option hardcodes a dollar figure on the page.

---

## Option 1: Annual-first Operator card on the Korvus landing

- **Stage moved:** Clicks to paid (landing to Operator checkout)
- **Idea:** Lead the Operator card with the annual plan, the 39.89 savings label, and a "LodeStone included" line. Monthly becomes the secondary option.
- **Number to watch:** Operator checkout starts divided by Operator paid conversions, per week, split by plan. Annual share of paid is the headline metric.
- **Status:** Not instrumented yet for plan-level checkout starts. Filing that instrumentation would come before judging this option.
- **What it triggers:** A proposal against `korvus:korvus_landing.html`, the pricing section. Regent reviews, the owner green lights in #boardroom, the executor applies.
- **Risk:** Changing layout could move the signup button. Keep the signup path unchanged and only reorder the plan cards.

## Option 2: Trader-voice X posts tagged to the Operator overlay

- **Stage moved:** Visits (X to korvus.industries)
- **Idea:** A short run of X posts written like a trader talking, built around one concrete product fact per post: the scored Presidential Wire read, the daily USD agenda, LodeStone on the chart. Each post ends with a UTM-tagged Korvus link. Two hashtags max.
- **Number to watch:** UTM-tagged visits from X, then UTM-tagged signups from X. The tagging is standing infrastructure, so no new filing is needed for the tags.
- **What it triggers:** Posts go direct from the server with the brand account's keys. Each post is 280 characters max, and a link counts as 23. Any video attach comes from Bard, with overlay lines baked on by the forge and no words in the footage itself.
- **Risk:** Posts must stay free of profit promises and trade calls. Every product claim carries the not-advice disclaimer.

## Option 3: Eclipse-X indicator room to Operator bundle

- **Stage moved:** Signups (Discord members to Korvus account)
- **Idea:** In #korvus-indicator, the people already using LodeStone learn that Operator includes TradingView access to it, at 79.99 a year with the 39.89 savings. This is a bundle explanation, not a discount, and it points at the annual plan.
- **Number to watch:** Discord join to Korvus signup conversion, measured through the UTM-tagged link in the channel. Signup to Operator paid conversion is the second number.
- **Guardrail:** The 149 one time Tradovate LodeStone and the 19.99 a month TradingView subscription stay separate in every line. Do not blur them into the Operator offer.
- **What it triggers:** Channel copy in Eclipse-X, which is community work and follows the value first rule: specific to the tools, no hype, no begging for activity.

---

## Recommendation

Option 2 is the fastest to run because its wiring is live. Option 1 is the highest leverage on paid but needs plan-level checkout instrumentation before the result can be read cleanly. Option 3 is the lowest cost and fits the Eclipse-X quota of 100 joins, but it depends on Discord members already being curious about the tools.

*Product claims are informational and educational. Nothing here is financial advice.*
