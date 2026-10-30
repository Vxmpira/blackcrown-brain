# Korvus-Site

korvus.industries, Flask. Live public routes only: /, /lodestone, /signup, /login, /legal, plus /p/<name> marketing pages.

## Guide portfolio (live, in sitemap)
- /p/es-vs-nq-beginners
- /p/paper-trade-futures
- /p/economic-calendar-futures
- /p/smt-divergence-explained
- /p/futures-margin-explained
- /p/futures-trading-sessions
- /p/what-moves-es-futures (X post live #327)
- /p/futures-tick-value-explained (X post live #328)
- /p/futures-vs-stocks-small-accounts (X post filed #331)

## In pipeline
- futures-rollover-explained: note 290 defective (duplicate meta description), scribe rewriting clean. Refile then sitemap entry.

## Known gaps
- korvus_landing.html does not link the /p/ guides. Internal links block needed; requires exact CURRENT anchor from the live file.
- Pricing is a section of korvus_landing.html (anchor id pricing), prices inject from Stripe tokens, never hardcode.

See [[Patterns]], [[Funnel]].