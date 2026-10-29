# Watcher Build Log

## 2026-10-29
- Target: korvus:pages/index-watch.html, serves at /p/index-watch.
- Style block: reported verified by copy minion, not yet assembled.
- Body attempt 1: returned truncated at the footer tag, closing tag not seen. Fail.
- Body attempt 2: asked for under 450 characters, ran past the cap and cut at the CTA anchor. Fail.
- Lesson: copy minion ignores length caps on single body runs. Split the body into two parts of about 500 characters each, each ending on a complete tag, and assemble only after both closing tags are seen.
- Next: part one (header, h1, intro, chips), part two (figure, CTA, footer). Verify, then assemble with the style block and the document wrapper.
- Not yet filed. No proposal until the closing html tag is verified in the full text.