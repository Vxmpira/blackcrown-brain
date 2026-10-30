# Korvus-Site

korvus.industries, Flask, only routed urls serve. Public: /, /lodestone, /signup, /login, /legal. New pages in pages/ serve at /p/<name>.

## Guide portfolio (live)
1. es-vs-nq-beginners
2. paper-trade-futures
3. economic-calendar-futures
4. smt-divergence-explained
5. futures-margin-explained
6. futures-trading-sessions
7. what-moves-es-futures
8. futures-tick-value-explained
9. futures-vs-stocks-small-accounts
10. futures-rollover-explained (filed #332, pending)

All live guides in sitemap. X launch post per guide is standard.

## Open equity moves
- Landing has zero links to /p/ guides. File internal link block once exact CURRENT landing text is in hand. See [[Patterns]].
- Related-links blocks inside guides, in progress.

Pricing is a section of korvus_landing.html (anchor id pricing), prices inject from Stripe tokens, never hardcode. See [[Funnel]].