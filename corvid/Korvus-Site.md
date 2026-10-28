# Korvus Site

Flask app, only routed urls serve. Repo prefix korvus:.

## Live public pages
- korvus_landing.html at /. Pricing is a section, anchor id pricing. Prices inject from Stripe, never hardcode dollars.
- korvus_lodestone.html at /lodestone
- korvus_signup.html, korvus_login.html, korvus_legal.html

## Never file SEO work on
- Gated: /terminal, /forex, /upgrade, /account
- Not served: trading_news_terminal.html, korvus_promo_studio.html, blackcrown-bar.html (robots blocked body fragment)

## /p guide pages (pages/ folder, serve at /p/name)
- futures-session-times-et, live, in sitemap
- prior-day-levels, live 10-28, in sitemap
- what-is-smt-divergence, live 10-28, in sitemap, X push filed as #234
- resting-liquidity, scribe drafting, file 10-29

robots.txt and sitemap.xml live and block gated pages. See [[Patterns]] and [[Keywords]].