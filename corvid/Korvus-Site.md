# Korvus-Site

Live public pages on korvus.industries. Linked from [[Patterns]] and [[Funnel]].

## Core routes
- / (korvus_landing.html, pricing section anchor id pricing, prices inject from Stripe, never hardcode)
- /lodestone, /signup, /login, /legal

## Guide pages, /p/ folder
- /p/es-vs-nq-beginners, live, in sitemap
- /p/paper-trade-futures, live 10-29 (#302), in sitemap (#304)
- /p/economic-calendar-futures, live, stray meta fixed (#303)
- /p/smt-divergence-explained, live 10-29 (#309), in sitemap (#307), canonical fix pending (#310)

## In the pipeline
- Sessions guide: refile pending (#318), sitemap pending (#314)
- Margin guide: pending (#319), sitemap files after approval
- ES movers guide: scribe note 284 written, files after margin, verify completeness first
- Cross-links: SMT guide linked FROM es-vs-nq and paper-trade, scout pulling exact anchors

## Laws
- One title tag per file, svgs use aria-label ([[Patterns]] healer lesson)
- New pages only in pages/ folder, serve at /p/<name>
- Dead ends: bar fragment, promo studio, dashboard, admin, agent. Never file.