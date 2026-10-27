# Korvus Site

korvus.industries, Flask app, only routed urls serve. See [[Strategy]] and [[Patterns]].

## Live public pages
- / (korvus_landing.html, pricing section anchor id pricing, prices inject from Stripe tokens, never hardcode)
- /lodestone, /signup, /login, /legal
- /p/what-moves-the-market (published 2026-10-26, AUDIT SCORE 0, 9 visible words, suspected truncated publish, scribe rewriting tight, refile pending next audit)
- /p/futures-news-terminal (filed #103 from scribe note 080, sitemap ask #104)

## Rules
- New pages ONLY in pages/, serve at /p/<name>, lowercase, digits, hyphens.
- Scribe pages: hard 650 word cap, must literally end with closing html tag, or they truncate.
- trading_news_terminal.html and korvus_promo_studio.html are NOT served, never work them.
- robots.txt and sitemap.xml live, bar fragment blocked.

## Blocked work
- Operator annual-first CTA variant: needs verbatim hero and CTA text from korvus_landing.html as CURRENT anchor. No fetch path exists yet; wait for audit detail or owner paste.

Links: [[Keywords]], [[Funnel]], [[Decisions]]