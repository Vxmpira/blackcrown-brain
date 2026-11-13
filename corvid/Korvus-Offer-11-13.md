# Korvus Offer 11-13

Copy for the 11-13 clip destination. Owner: [[Corvid]]. Requested by Bard. Rung: first paying customer.
Status: COPY ONLY. Not a page yet, not filed. The html build waits on Page-Frame and the filing hold.

## Key line for Bard (inline, under 80 words)
Headline: The market does not sleep. Korvus does not blink.
Sub: A 24/7 intelligence terminal for index futures traders. It explains why price moved. It never predicts where it goes.
CTA: Start free as Observer.
Destination until the page ships: korvus.industries/signup with the standing UTM tags.

## Why this page
- 7d visits 89 (prev 24). Analyst 354 read the lift as probably not human led: 1 click to Korvus on 90 visits, 1.1 percent.
- Human-only visit count: not instrumented yet.
- The page has one job: turn a clip viewer into an Observer signup, with Operator one scroll away. Success metric is clicks to /signup, not visits.

## Page copy

### Hero
Eyebrow: KORVUS. MARKET INTELLIGENCE TERMINAL
H1: The market does not sleep. Korvus does not blink.
Sub: A 24/7 intelligence terminal for index futures traders. Scored news, the futures board, cross index SMT divergence, and session and macro context, assembled into one directional read. It explains why price moved. It never predicts where it goes.
Primary button: Start free as Observer (to /signup)
Secondary link: See Operator pricing (to the offer section on this page)
Micro line under the buttons: Information and education only. Not financial advice.

### Section 2. The problem
H2: You woke up to a move you did not see.
Body: Headlines land overnight. A session opens. A data print hits. By the time you have eight tabs open, the context is already gone. Korvus keeps watch through all of it and hands you the read in one place, so you start the session knowing what happened and why.

### Section 3. What is on the terminal
H2: One screen. The whole picture.
Feature chips, four:
- Scored news feed. Every headline rated, so you know what matters before you read it.
- Futures board. The index futures you trade, side by side.
- Cross index SMT divergence. See when the indexes stop agreeing.
- Session and macro context. Where you are in the day and what is on the calendar.
Closing line: All of it assembled into a directional read, with the reasoning written out.

Visual, required: a data mock of one scored wire card with four fields, Impact, Direction, Confidence, and a two line written Korvus read. Placeholder values only. Label it Illustration in the corner.

### Section 4. The offer
H2: Start free. Upgrade when it earns it.
Card 1, Observer: Free. Watch the terminal work before you pay for anything.
Card 2, Operator, annual listed first: 79.99 a year. Label: Save 39.89 a year versus monthly. Or 9.99 a month.
Operator line: Includes the LodeStone TradingView indicator, which is 19.99 a month on its own.
Button on both cards: Start free as Observer (to /signup)
Note under the cards: Not financial advice. No profit is promised.

### Section 5. The honest part
H2: What Korvus is not.
Body: No signals. No calls. No promises. Korvus is built by a solo operator who trades index futures himself, for traders who want the context and will make their own decisions. If you want someone to tell you what to buy, this is the wrong tool.

### Final CTA
H2: Your edge while the world sleeps.
Button: Start free as Observer (to /signup)

### Footer disclaimer
Korvus provides market information and education only. Nothing here is financial advice or a recommendation to trade. No profit is promised. Trading futures carries risk of loss.

## Build notes for the Scribe pass
- Build inside the Page Frame skeleton with the inline crown SVG in the header. Tables go in a tablewrap rail.
- Container about 1060px, clamp() headings, prose at reading width, chips and cards collapsing under 700px.
- Background: soft accent glows, faint grid, edge vignette. No images, nothing animated.
- Suggested route: korvus:pages/watcher.html, serving at /p/watcher.
- Savings math: 12 x 9.99 = 119.88, minus 79.99 = 39.89, about 33 percent.
- No em dashes, no emoji.

## Open items, stated plainly
- I have not seen the 11-13 clip direction. If the clip is not the watcher angle, the H1 changes and the rest holds.
- The Observer versus Operator feature split is not in my feed, so the copy does not claim one. Add it only from the live pricing section.
- Whether /p/ pages can use the Stripe display tokens is unknown. If they can, use tokens instead of typed prices.
- Whether Observer signup needs a card is not confirmed, so the copy makes no card claim.