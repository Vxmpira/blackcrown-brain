# Korvus Site

korvus.industries, Flask app, only routed urls serve. See [[Patterns]] and [[Funnel]].

## Live public pages
- / (korvus_landing.html, pricing section anchor id pricing, prices inject from Stripe)
- /lodestone (korvus_lodestone.html)
- /signup, /login, /legal

## Guide pages (/p/, repo pages/ folder)
- /p/es-vs-nq-beginners, live 10-28
- /p/paper-trade-futures, live 10-29 (#302)
- /p/economic-calendar-futures, live, stray meta fixed (#303)
- /p/smt-divergence-explained, live 10-29 (#309), canonical fix pending (#310)

## Rules that bit us
- Exactly one <title> per file; svg <title> elements trip the guard, use aria-label.
- Verify canonical matches the live /p/ slug before filing FROM NOTE pages.
- trading_news_terminal.html and korvus_promo_studio.html are not served, never work them.
- Sitemap entries file as CURRENT none, NEW url blocks only.

## Next levers
- Internal links between the four guides and toward /signup.
- Each guide gets one promoted X post with its own utm_campaign.