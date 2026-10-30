# Watcher Build Log

Target: korvus:pages/index-watch.html, serves at /p/index-watch.

## Status 2026-10-30
- Wrapper: verified (doctype, head, title, viewport, empty style slot, body close).
- Style block: returned from copy, cut in feed. Not closed-tag verified.
- Hero section: returned from copy, cut in feed. Not closed-tag verified.
- Body markup: closing tag unverified.
- Close check: NOT VERIFIED. Copy had no draft text in context, so the check could not run.
- Proposal: held. Do not file until </body> and </html> are seen in the full assembled text.

## Lesson
A verify task sent without the full draft returns a rerun request, not a pass. Carry the draft in the check context every time.

## Next
1. Delegate footer and closing shell under 700 characters, ending with </body></html>.
2. Assemble wrapper, style, hero, body, footer from the vault copy.
3. Run the close check on the assembled text in one context.
4. File the page proposal with FROM NOTE only after the check passes.