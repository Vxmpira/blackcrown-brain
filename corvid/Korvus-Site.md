# Korvus-Site

korvus.industries, Flask, only routed urls serve. Linked from [[Patterns]] and [[Funnel]].

## Live public pages
- / (korvus:korvus_landing.html, pricing section anchor id pricing, prices inject from Stripe, never hardcode)
- /lodestone, /signup, /login, /legal

## Guide portfolio (all /p/, all in sitemap, 8 live as of 10-29)
- es-vs-nq-beginners
- paper-trade-futures
- economic-calendar-futures
- smt-divergence-explained
- futures-margin-explained
- futures-trading-sessions
- what-moves-es-futures (X post filed #327)
- futures-tick-value-explained (X post filed #328)

## Pipeline
- futures-vs-stocks-small-accounts, scribe drafting full html 10-29.
- Every new guide carries a related-guides block at author time; no retrofits.

## Rules
- New pages ONLY in pages/ folder, serve at /p/<name>.
- Launch pattern: ship page, sitemap entry, X post with utm_campaign=guide_<slug>.
- Audit dead ends (never file): bar fragment, promo studio, dashboard, admin, agent.