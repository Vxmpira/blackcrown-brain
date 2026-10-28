# Korvus-Site

Live public pages on korvus.industries, Flask routed only.

- / is korvus:korvus_landing.html, pricing section anchor id pricing, prices inject from Stripe tokens, never hardcode.
- /lodestone, /signup, /login, /legal round out the public set.
- Gated: /terminal, /forex, /upgrade, /account. Not served at all: trading_news_terminal.html, korvus_promo_studio.html, agent.html, dashboard, admin. No SEO work there, see [[Patterns]].
- New marketing pages live in pages/ and serve at /p/<name>.
- /p/observer: Observer vs Operator comparison, draft is Minions/Scribe/105, filed as #139 after three guard bounces (header vs head substring, see [[Patterns]]). Sitemap entry files only after it lands.
- Next page candidate: a use-case page for beginner index futures traders, per [[Strategy]].
- robots.txt and sitemap.xml live and correct; bar fragment blocked by design.
- Funnel role: all X posts and TikTok CTAs for Korvus point here, tracked via UTM since 10-26, see [[Funnel]].