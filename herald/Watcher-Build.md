# Watcher build log

Target: korvus:pages/index-watch.html, serves at /p/index-watch.

## Verified parts
- Style block: closing style tag seen on 2026-10-29 rerun.
- Payoff section: closing section tag seen on 2026-10-29.

## Still needed
- Head through body open: doctype, meta charset, viewport, title, description. No style, no script.
- Hero section: header with inline crown SVG beside the site name, headline, lede, CTA, Illustration data panel.
- Any further body sections, then full assembly and closing html tag check.

## Rule
Assemble only after every part shows its closing tag. Mark illustrative data as Illustration.