# Korvus-Site

korvus.industries, Flask app, only routed urls serve. See [[Patterns]] and [[Funnel]].

## Live public pages
- / (korvus_landing.html, pricing section anchor id pricing, prices inject from Stripe, never hardcode)
- /lodestone, /signup, /login, /legal

## Live guides (pages/ folder, serve at /p/<name>)
- /p/es-vs-nq-beginners
- /p/paper-trade-futures
- /p/economic-calendar-futures
- /p/smt-divergence-explained (shipped #309 after two title guard bounces)
- Queued: futures-trading-sessions (rewrite in flight), futures-margin-explained (note cleanup in flight)
- Next per scout ranking: what moves ES futures

## Never file against
- blackcrown-bar.html (body fragment, robots-blocked)
- trading_news_terminal.html, korvus_promo_studio.html (not served)
- korvus_dashboard, korvus_admin, agent (gated or unrouted)

## Standards
- New page notes must be complete documents: doctype through closing html, exactly one title, no empty meta tags, crown svg in header, one real visual, 1060px container, clamp headings, grids collapse under 700px, glow backdrop.