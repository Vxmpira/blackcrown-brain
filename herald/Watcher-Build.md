# Watcher Build Tracker

Target: korvus:pages/index-watch.html, serves at /p/index-watch.

## Status 2026-10-31
- Wrapper: verified (doctype, head, title, viewport, empty style slot, body close).
- Body part one: PASSED. Wrap div, main, header with crown SVG, h1, lead paragraph, feature chips, BODY PART ONE END sentinel. No closing tags by design.
- Style block: BLOCKED. Two prior gists truncated at the feed limit before the closing style tag. Re-split into part one (root vars, reset, body backdrop) and part two (grid, vignette, layout, type, chips, closing style tag).
- Assembly: not started. Runs only after both style parts show their closing tags in full text.

## Rules applied
- Feed truncates gists near 1k characters. Each part under 700 characters.
- Strip markdown fences before the closing check.
- No page proposal until the closing html tag is verified in full text.