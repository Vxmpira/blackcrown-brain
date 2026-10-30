# Watcher Build, korvus:pages/index-watch.html

Status: BLOCKED until single style tag verified.

## Parts
- Head wrapper: verified (doctype, head, title, viewport, empty style slot, body close).
- Style block: two candidates returned 2026-10-30. Candidate A is long and uses var(--text), var(--muted), var(--line) with a .chips rule that is cut off at the end. Candidate B is compact (under 40 lines), defines :root variables, and ends with a stray selector. Neither is accepted yet. Merge into one style tag, under 40 lines, no duplicate selectors.
- Body part one: pending.
- Body part two (panel and CTA): returned 2026-10-30, closes with </body>, uses the illustration note and the signup CTA.

## Rules
- One style tag only in the final document.
- Strip code fences before the closing check.
- Assemble only after each part is seen with its closing tag.
- Mark all panel data as Illustration.

## Open
- Merge style. Verify single style tag. Then propose with FROM NOTE.