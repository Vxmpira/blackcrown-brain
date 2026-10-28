# Korvus Site

korvus.industries, Flask app. Live public: /, /lodestone, /signup, /login, /legal, plus /p/<name> pages from the pages folder.

## /p keyword pages
- /p/observer: live, in sitemap, UTM-tagged destination for Operator clips and X posts.
- /p/smt-divergence: in sitemap, 404. Refiled #167 as verbatim whole-file write from Scribe note 114.
- /p/ict-killzones: in sitemap, 404. Refiled #168 as verbatim write from Scribe note 115.
- Next in [[Keywords]]: /p/premium-discount, /p/liquidity-sweep. Do not draft until 167 and 168 land clean.

## Publish saga, lesson
Two clean single-head documents bounced the duplicate-head guard twice (#158, #164, #165). Conclusion in [[Patterns]]: the executor merge path duplicates the head on new-file writes. Fix filed: explicit verbatim whole-file writes. If that bounces too, this is an infrastructure bug for Regent, not a copy problem.

## Standing facts
- Pricing injects server side from Stripe tokens on korvus_landing.html, never hardcode dollars.
- trading_news_terminal.html and korvus_promo_studio.html are not served; zero SEO work there.
- Funnel target: home leak, 28 of 33 visits land on brand home with 0 Korvus clicks this week. See [[Funnel]].