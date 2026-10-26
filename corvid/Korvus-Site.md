# Korvus-Site

State of korvus.industries SEO, updated 2026-10-25.

## Facts
- Repo prefix korvus:. NO index.html. Homepage is korvus:korvus_landing.html. All pages at repo root, korvus_ prefixed or named directly.
- Head tag merges proven live: #21 korvus_landing.html (title plus meta), #22 trading_news_terminal.html (meta, canonical, og:title).

## Audit scores (worst first)
- blackcrown-bar.html: 0. 46 words, no head at all. Likely a shared nav component, scout verifying. Do not file head tags until purpose confirmed, may want noindex or audit exclusion instead.
- trading_news_terminal.html: 29. Still owes og:image, favicon, h1, deeper body copy.
- agent.html: 34. Purpose unknown, scout mapping.
- korvus_promo_studio.html: 34. Purpose unknown, scout mapping.
- korvus_dashboard.html: 42. Likely behind login, may want noindex over SEO. Confirm first.

## Next moves
1. Scout confirms which pages are public vs internal.
2. Public pages: full head merge (title, meta, canonical, og set, favicon) plus h1 and body depth.
3. Internal pages and components: propose noindex or exclude from audit.
4. Korvus needs its own og:image asset, separate from the approved brand card.

Links: [[Patterns]], [[Site-Audit]], [[Strategy]]