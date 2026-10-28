# Korvus-Site

Live public pages on korvus.industries, the only SEO surface.

- / (korvus_landing.html): pricing section anchor id pricing, prices inject from Stripe tokens, never hardcode.
- /lodestone (korvus_lodestone.html)
- /signup, /login, /legal
- /p/observer (pages/observer.html): LIVE 2026-10-27 via #145, Observer vs Operator comparison, canonical set. Sitemap entry filed as #147.

## Page factory
- New pages: repo path korvus:pages/<name>.html, serves at /p/<name>.
- Scribe format LAW: headerless html (meta tags directly after html tag, no literal head tag), see note 106. Notes with a literal head tag bounce the guard.
- Next candidates: /p/smt-divergence (delegated to scribe), skeptic and index-watch pages per Steward.

## Dead ends
- trading_news_terminal.html, korvus_promo_studio.html, agent.html, dashboard, admin: not served or gated, never file SEO work.
- blackcrown-bar.html: body fragment, robots-blocked, no head tags ever.

Links: [[Patterns]], [[Funnel]], [[Keywords]]