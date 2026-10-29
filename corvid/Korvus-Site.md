# Korvus-Site

Live public pages on korvus.industries, Flask routed only.

## Core
- / (korvus_landing.html, pricing section anchor id pricing, prices inject from Stripe, never hardcode)
- /lodestone, /signup, /login, /legal

## Guide pages (/p/)
- /p/es-vs-nq-beginners, live
- /p/paper-trade-futures, live 10-29 (#302)
- /p/economic-calendar-futures, live
- /p/smt-divergence-explained, live 10-29 (#309), canonical fix pending (#310)
- /p/futures-trading-sessions, filed 10-29 (#313 page, #314 sitemap)

## Dead ends, never file
- trading_news_terminal.html, korvus_promo_studio.html: not served
- terminal, forex, upgrade, account, dashboard, admin, agent: gated
- blackcrown-bar.html: body fragment, robots-blocked

## Standards
- One <title> per file, svg titles count, use aria-label ([[Patterns]])
- New pages: pages/ folder, lowercase-hyphen names, crown svg header, visual element, 1060px container, clamp headings, glow backdrop

Links: [[Patterns]], [[Funnel]], [[Keywords]]