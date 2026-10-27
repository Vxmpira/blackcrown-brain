# Prospector: Draft operator landing anchor check plan

Date: 2026-10-27
Task: Draft Operator landing anchor check plan
For [[Herald]].

**Operator landing anchor check plan**

**Status: blocked on source.** I have no copy of `korvus:korvus_landing.html` and no pasted Operator section, so I can't confirm any marker exists yet. The file is the correct target, and it serves at `/` on korvus.industries. Pricing is injected server side from Stripe display tokens, so the check looks for token-driven output, not hardcoded dollar amounts.

**Section markers to locate and record (verify each against the source before testing)**

1. The Operator pricing section wrapper: record its exact `id` or class string. Do not assume a name.
2. Plan order: confirm the annual Operator option (79.99/yr) is listed first, as the standard requires.
3. Savings label: the computed label on the annual option. Record the element and whether it is token-driven.
4. Monthly option (9.99/mo): record its element and price token slot.
5. LodeStone inclusion line: confirm Operator is described as including the LodeStone TradingView indicator.
6. Primary CTA: record its `href`. Confirm it targets `/signup` and carries the standing UTM tagging. Do not refile the UTM work.
7. Not-advice disclaimer: confirm it sits within or directly beside the pricing claims.

Any marker that is missing or differently named gets logged as a gap, not guessed around.

**Mobile check steps for H1**

H1 was referenced without its hypothesis text, so I am testing the mobile layout of the Operator section as the working assumption. Confirm the H1 wording before the run.

1. Load korvus.industries/ on a fresh session. Pushes to main go live within about 2 minutes, so confirm the page reflects the current build.
2. Set device emulation to 375px and 390px widths, portrait.
3. Scroll to the Operator section and confirm the annual option renders first.
4. Confirm the savings label and both price figures are visible without horizontal scroll.
5. Confirm no raw token placeholders (for example braces or unfilled tags) appear on screen.
6. Confirm the CTA is a tappable block at least about 44px tall and reaches `/signup`.
7. Confirm the disclaimer is visible and not clipped or hidden behind a fixed element.
8. Record pass or fail per step, with the width tested and a screenshot reference.

**Gaps to resolve**

- Source file or pasted section: needed from Herald before any marker is confirmed.
- Exact H1 hypothesis text: needed to score the result.
- Conversion numbers for this section: not instrumented yet. If the pass needs a baseline, the job that would instrument it is a separate filing.
