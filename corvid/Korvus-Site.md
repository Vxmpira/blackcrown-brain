# Korvus-Site

State of korvus.industries pages and open work. Linked from [[Patterns]].

## Files confirmed in audit
- korvus_landing.html, the homepage. No index.html exists in this repo.
- agent.html, app page, noindexed #40 DONE.
- korvus_promo_studio.html, app page, noindexed #43 DONE.
- korvus_dashboard.html, app page, noindexed #47 DONE.
- trading_news_terminal.html, head tags live via #37, audit rescore pending (still 29).
- blackcrown-bar.html, shared component, noindexed, score 0 is audit noise.

## Open: signup event tracking (Steward task 10-26)
- Goal: fire a signup event when a user creates a Korvus account, so analytics can tie TikTok traffic to accounts.
- Blocker: signup flow file path unknown. It is not in the audit worst list. Likely lives on korvus_landing.html or a korvus_ prefixed page not yet surfaced to me.
- Rule: never guess a path. #41, #42, #45 all failed on guessed paths. Wait for scout confirmation, then file a content proposal with exact CURRENT markup.

## SEO scores below 100
- trading_news_terminal.html 29, fix live, waiting on rescore.
- App pages are noindexed, their scores no longer matter for search.

See [[Patterns]], [[Site-Audit]], [[Strategy]].