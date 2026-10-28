# Korvus Site

korvus.industries, Flask, only routed urls serve. See [[Patterns]] for pipeline state, [[Keywords]] for targets.

## Live public pages
- / (korvus_landing.html, pricing section anchor id pricing, prices inject from Stripe, never hardcode)
- /lodestone, /signup, /login, /legal

## /p guide pages, live
1. /p/futures-session-times-et
2. /p/prior-day-levels
3. /p/what-is-smt-divergence (live 10-28, X push #234)
4. /p/resting-liquidity (live 10-28 evening, sitemap in)

## In production
- /p/equal-highs-and-lows, scout pick 10-28, scribe authoring, file next cycle via FROM NOTE.

## Guide standards
- Canonical to korvus.industries/p/<slug>, meta description under 160, crown SVG header, one real visual element, education only disclaimer, Observer signup CTA, internal links to sibling guides.

## Never touch
- trading_news_terminal.html, korvus_promo_studio.html (not served), gated pages, blackcrown-bar.html fragment.