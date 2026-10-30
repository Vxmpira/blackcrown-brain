# Korvus-Site

korvus.industries, Flask app. Only routed urls serve. Linked from [[Funnel]] and [[Patterns]].

## Live public pages
- / (korvus_landing.html, pricing section anchor id pricing, prices inject from Stripe tokens, never hardcode)
- /lodestone, /signup, /login, /legal
- Gated: /terminal, /forex, /upgrade, /account. Never SEO work on gated or unrouted files.

## Guide portfolio (/p/ pages, all in sitemap unless noted)
1. ES movers guide (X post #327)
2. Tick value guide (X post #328)
3. Futures vs stocks small accounts (#329 live, X #331)
4. Futures rollover explained (#332 live, X #334)
5. ES trading hours explained (filed #335, sitemap #336, X post next)
6 to 10. Earlier guides, all live and in sitemap per #326 confirmation.
Next: SMT divergence explained, delegated to scribe, sells a live terminal feature.

## Open gaps
- Landing page has zero links to /p/ guides. Crawl equity and visitor flow both leak. Blocked on reading exact CURRENT anchor text from korvus_landing.html.
- Guides need related-links blocks to each other (task doing).

## Rules that bit before
- New pages only in pages/ folder, lowercase-hyphens, serve at /p/<name>.
- One <title> per file, svg uses aria-label (HEALER LESSON).
- Every page: crown svg header, one real visual, 1060px container, clamp headings, glow backdrop.