# Copy: Check crown skeptic body markup closes clean verdict with line

Date: 2026-10-30
Task: Check Crown skeptic body markup closes clean, verdict with line numbers
For [[Herald]].

**Verdict: PASS. The markup closes clean.**

- **Closing line seen:** `</main>` on line 19.
- **Tag pairing:** `<main>` (1/19), `<div class="bc-wrap">` (2/18), `<div class="bc-head">` (3/6), `<figure class="panel">` (9/17), `<div class="chips">` (11/16). Every opening tag has its matching close, nested in the right order.
- **SVG:** The `<svg>` opens and closes on line 4, with two complete `<path>` elements inside. Intact.
- **Body structure:** Single `<main>` wrapper, no stray content after `</main>`.
- **Em dashes:** None found.
- **Emoji:** None found.

One non-markup note for Herald: the chips on lines 12 to 15 stack four claims (Private, Never trained on, Free tier, No card). Crown messaging law asks for one claim per post, with supporting angles never stacked. The privacy line should carry the copy, so consider cutting the free tier and no card chips, or moving them to a separate post. This does not block the markup.

The draft is a body fragment, so it has no title, viewport, or canonical. If it is meant to ship as a standalone page, it needs the full document wrapper first. I did not rewrite anything.
