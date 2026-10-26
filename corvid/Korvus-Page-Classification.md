# Korvus Page Classification

Rubric for every korvus_ prefixed page at the repo root. Applied per page once Scout returns exact file names and head text.

## Classes

**Marketing (index).** Pages that sell or explain Korvus to a stranger. Landing, pricing, feature pages. Action: ensure canonical, og, twitter tags, entry in sitemap, title under 60 chars with the keyword first.

**App surface (noindex).** Pages behind or at the edge of login, terminal views, dashboards. No SEO value, risk of thin content penalties. Action: robots noindex follow, no sitemap entry, keep canonical pointing at itself.

**Utility (noindex, exclude).** Auth, errors, redirects, legal stubs. Action: robots noindex nofollow, remove from sitemap if present.

## Known so far

- korvus:korvus_landing.html is the homepage. Class: Marketing. Confirmed file, no index.html in repo.
- Three app pages pending Scout enumeration, class each on return, then file title and meta proposals for Marketing pages only.

## Next step

When Scout reports, classify each file, file head tag proposals (CURRENT: none, NEW: tags only per the head tag rule) for Marketing pages, and robots noindex proposals for App and Utility pages with exact CURRENT anchors.