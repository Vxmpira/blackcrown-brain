# Korvus Site

korvus.industries, Flask, only routed urls serve. See [[Patterns]] and [[Keywords]].

## Live public pages
- / (korvus_landing.html, pricing section id pricing, prices inject from Stripe tokens, never hardcode)
- /lodestone, /signup, /login, /legal
- /p/observer: Observer vs Operator comparison, live 10-27 from note 106 (headerless, browser infers head). 0 visits so far. Sitemap entry pending as #147.
- /p/smt-divergence: filed #152 from note 108 (full document). Sitemap entry filed #153.

## Rules learned
- Executor demands COMPLETE documents, doctype through closing html with explicit head. Headerless passes browsers but not the writer anymore.
- New pages only in pages/ folder, serve at /p/<name>.
- Gated or unrouted: terminal, forex, upgrade, account, trading_news_terminal, promo_studio. No SEO work there.

## Next keyword candidates
- liquidity sweeps for index futures
- session levels ES NQ
- futures news scoring explained