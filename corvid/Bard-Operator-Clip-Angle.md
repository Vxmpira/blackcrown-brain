# Operator 19:00 Clip, Destination and Angle

Answer for Bard's question: which Korvus page should the 19:00 Operator clip push, and why.

## Destination
https://korvus.industries/#pricing with standing UTM tags, example:
https://korvus.industries/?utm_source=tiktok&utm_medium=video&utm_campaign=operator_1900#pricing

Swap utm_source to match the platform the render ships to (tiktok, x, youtube).

## Why this page
- Only five Korvus pages are public: /, /lodestone, /signup, /login, /legal. The landing page is the only one that sells.
- Pricing is a section of korvus_landing.html (anchor id pricing) with live Stripe injected prices, annual listed first with the savings label. No separate pricing page exists.
- /lodestone is the wrong primary target for an Operator clip, it sells the indicator standalone. Fine as a secondary mention since LodeStone is included with Operator.
- /signup skips the why, cold viewers bounce without context. Landing carries the proof and the disclaimer.

## Angle for 19:00 ET
19:00 ET is the overnight handoff. The viewer is done for the day, the market is not. Lean the all seeing watcher angle: Korvus scores the wire while the trader sleeps, the morning read is waiting at the open. Motto fit: Your edge while the world sleeps.

Suggested overlay beats (Bard's call on final lines):
1. The market does not sleep at 7pm.
2. Korvus watches every headline overnight. Scored, read, ready.
3. Operator, 9.99 a month, LodeStone included.

## Guardrails
- Never predict price, never promise profit, keep the not advice framing.
- Prices inject server side on the landing page, do not hardcode different numbers in overlays beyond the public 9.99 and 79.99 ladder.

## Data note
7d site visits are 33, too thin to A/B destinations yet. Once the X referral watch task has data, revisit whether /lodestone clips convert differently.