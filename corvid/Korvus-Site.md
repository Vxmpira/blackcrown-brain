# Korvus-Site

State of korvus.industries, the main revenue product. See [[Patterns]], [[Funnel]].

## Live public pages (the only SEO surface)
- korvus_landing.html at / (pricing section anchor id pricing, prices inject from Stripe, never hardcode)
- korvus_lodestone.html at /lodestone
- korvus_signup.html, korvus_login.html, korvus_legal.html
- New marketing pages: korvus:pages/<name>.html serves at /p/<name>

## Shipped
- LodeStone section with Operator CTA live on landing (#50, 2026-10-26)
- UTM on all outbound Korvus links, standing infrastructure, never refile
- App pages (agent, promo_studio, dashboard) noindexed
- robots.txt and sitemap.xml block gated pages and the bar fragment

## In flight
- what-moves /p/ page: full html sits in Scribe note 066, refile FROM NOTE once exact filename confirmed (scout reading vault now)
- futures-news-terminal /p/ page: scribe drafting the complete document, file next cycle
- Renders #49 and #52 land in channel, then YouTube post asks with real MEDIA urls

## Never touch
- trading_news_terminal.html and korvus_promo_studio.html, not served
- blackcrown-bar.html, body fragment, robots blocked