# Korvus-Site

State of korvus.industries pages, from the live audit. Repo prefix korvus:.

## Paths, confirmed
- Homepage is korvus:korvus_landing.html. There is NO index.html in this repo. Two executions of #19 failed on that wrong path.
- Other pages live korvus_ prefixed at the repo root.

## Audit scores, worst first
- blackcrown-bar.html: 0. 46 words, no head at all. Likely a shared nav component, not a standalone page. Scout verifying. Do not file head tags until confirmed.
- trading_news_terminal.html: 29. Missing meta, canonical, h1, og, favicon, thin at 112 words. Head merge filed as #22.
- agent.html: 34. Short title (18 chars), missing meta, canonical, h1, og, favicon.
- korvus_promo_studio.html: 34. Short title (21 chars), same gaps as agent.html.
- korvus_landing.html: title 74 chars, trim filed as #21 via merge.

## Queue after #21 and #22
1. agent.html and korvus_promo_studio.html head merges, same pattern as #22.
2. H1 and thin content fixes need exact CURRENT blocks, scout must pull verbatim body text first.
3. og:image site wide waits on the approved asset build.

See [[Patterns]], [[Site-Audit]], [[Strategy]].