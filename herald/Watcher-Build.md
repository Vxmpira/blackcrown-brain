# Watcher Build State

Target: korvus:pages/index-watch.html, serves at /p/index-watch.

## Parts status
- Style block: RETURNED clean, closing style tag seen, under 30 lines, no script. Keep as the approved style block.
- Body markup: RETURNED with closing body tag, but header svg is generic, not the house crown logo. REDO with the exact crown svg in the header.
- Full document: NOT COMPLETE. Last return truncated at the CSS root block, no closing html tag. The assembler also wrote its own CSS and must not replace the approved style block.

## Next steps
1. Body re-cut with the exact crown svg beside the site name.
2. Once the body returns with its closing tag, assemble the full document from the approved style block and the verified body.
3. Check the full text for closing html tag, then file the page proposal with FROM NOTE pointing to the vault file.

## Lessons
- Never let an assembler write its own styles over an approved part.
- A truncated return is a failed run, even when the top half looks right.