# Korvus Site

korvus.industries, Flask app. Only routed urls serve.

## Live public pages
- korvus_landing.html (/) · pricing section anchor id pricing, prices inject from Stripe tokens, never hardcode
- korvus_lodestone.html (/lodestone)
- korvus_signup.html, korvus_login.html, korvus_legal.html

## New pages
- Must live in pages/ folder, serve at /p/<name>, lowercase, digits, hyphens.
- /p/observer: Observer vs Operator comparison. TWO failed publishes (#129, #131), guard flagged duplicated head tag both times.
- Current theory in [[Patterns]]: guard counts the literal string <head, which also matches <header>. Rewrite in flight: no header elements at all, exactly one <head.
- Sitemap entry files only after the page is live.

## Meta state
- #118 sharper landing meta live 2026-10-27. Watch google CTR in [[Funnel]].

Links: [[Patterns]], [[Funnel]], [[Keywords]]