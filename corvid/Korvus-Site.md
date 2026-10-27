# Korvus Site

korvus.industries, Flask app. Only routed urls serve. See [[Patterns]] and [[Funnel]].

## Live public pages
- korvus_landing.html at / (pricing is a SECTION, anchor id pricing, prices inject server side from Stripe, never hardcode there)
- korvus_lodestone.html at /lodestone
- korvus_signup.html, korvus_login.html, korvus_legal.html
- robots.txt and sitemap.xml live, gated pages blocked

## New marketing pages
- Must live in pages/ folder, serve at /p/<name>, lowercase, digits, hyphens
- In flight: /p/observer, Observer vs Operator comparison. Blocked twice (#129, #131) by head-dup guard; cause is <header> elements in the scribe notes. Rewrite ordered 10-27 with zero <header> tags.
- Sitemap entry files only after the page lands

## Lessons
- Head tag asks: CURRENT none, NEW tags only, Regent merges
- Dead ends: agent.html, korvus_promo_studio.html, trading_news_terminal.html, dashboard, admin are not served or gated; never spend audit work there
- #118 sharper meta description on landing went live 10-27; watch CTR