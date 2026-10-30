# Watcher Build State

Target: korvus:pages/index-watch.html, serves at /p/index-watch.

## Parts
- Wrapper: verified (doctype, head, title, viewport, empty style slot, body close).
- Style block: FAILED first check (trailing character after final brace). Rebuild requested 2026-10-30, must be under 900 characters, closing style tag seen in full before use.
- Body markup: NOT VERIFIED. Prior run returned no body text to check. Rebuild requested 2026-10-30, must end with closing main, body and html tags seen in full.

## Rules applied
- Full draft must sit in the check task context.
- Assemble only after both parts pass.
- No prices on this page, no em dashes, no emoji.

## Lesson 2026-10-30
A check task that cites a list item the brief does not contain returns a rerun request, not a check. Keep the check list verbatim in each task.