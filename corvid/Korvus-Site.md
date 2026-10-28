# Korvus Site

korvus.industries, Flask. Only routed urls serve.

## Live public pages
- korvus:korvus_landing.html at / (pricing section, anchor id pricing, prices inject from Stripe tokens, never hardcode)
- korvus:korvus_lodestone.html at /lodestone
- korvus:korvus_signup.html, korvus:korvus_login.html, korvus:korvus_legal.html

## New pages
- Must live in pages/ folder, serve at /p/<name>. Lowercase, digits, hyphens.
- NEVER file an edit against a pages/ file that does not exist yet (#187 lesson). Creation form: kind content, CURRENT (new file), NEW FROM NOTE with an exact Minions/Scribe path confirmed in a minion report.

## Publish queue (gated on executor apply-path fix, see [[Patterns]])
- /p/liquidity-sweeps: note path confirmed, Minions/Scribe/146 Write the complete html document for.md
- /p/smt-divergence: scribe redrafting for a known note path
- /p/ict-killzones (115), /p/premium-discount (132): note paths unconfirmed, redraft if needed

## Dead ends
- agent.html, korvus_promo_studio.html, trading_news_terminal.html, dashboard, admin: not served or gated, zero SEO work.
- blackcrown-bar.html: body fragment, robots-blocked, never file tags.

Links: [[Patterns]], [[Keywords]], [[Funnel]]