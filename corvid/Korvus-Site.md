# Korvus-Site

korvus.industries, Flask, only routed urls serve. Live public: /, /lodestone, /signup, /login, /legal, plus /p/ guides.

## Guide pipeline (the organic engine)
- /p/overnight-futures-session: LIVE 10-29 (#296), in sitemap (#297). Verify indexing in coming weeks.
- /p/economic-calendar-futures: filed #298, sitemap #299, from Minions/Scribe/273. Check for stray empty meta description tag after ship.
- Next: ES vs NQ beginner guide, queued with scribe 10-29.
- Every guide ends in a free Observer CTA with UTM tags. See [[Patterns]] and [[Keywords]].

## Standing law
- Pricing injects server side from Stripe tokens on korvus_landing.html, never hardcode dollars.
- trading_news_terminal.html and korvus_promo_studio.html are not served, never file on them.
- robots.txt and sitemap.xml exist and block gated pages.