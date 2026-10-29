# Watcher build status

Target: korvus:pages/index-watch.html, serves at /p/index-watch.

## Parts
- Wrapper: verified. Doctype, head, title, viewport, empty style slot, body close.
- Style block: verified 2026-10-29. Returned complete through </style>, under 700 characters.
- Figure SVG: partial. Returned from the wfill gradient through </figure>. Missing the opening figure tag, the opening svg tag and the defs open. Rerun requested.
- Body tail: partial. Returned through </body>. Closing </html> not seen. Rerun requested.

## Gate
Do not assemble or file until every part shows its closing tag in the returned text. Each part is its own delegation, each under 700 characters.

## Lessons
- Copy gists truncate past roughly 1k characters. Split pages into head, figure, body and style parts.
- A part that starts mid element is a failed return, even if its end tag is present.