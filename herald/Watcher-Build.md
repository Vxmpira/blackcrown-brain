# Watcher build state, 2026-10-29

Target: korvus:pages/index-watch.html, serves at /p/index-watch.

## Parts
- Wrapper (doctype, head, title, viewport, body close): verified earlier.
- Header and hero markup: returned with closing tags. Verified.
- Style block: a standalone replacement is being rebuilt. The earlier tail was returned with </style> but its opening lines were lost in the feed, so it cannot be spliced.
- Body sections: next delegation, one section per part.

## Lesson
Copy minions share no context between calls. Every part must carry its own class map and every needed rule. A split page only assembles when each part is standalone or the seam is verified in the full text.

## Status
Not assembled. No proposal filed until the closing html tag is verified in the full document.