# Korvus Site

korvus.industries, Flask. Only routed urls serve. See [[Patterns]] for audit dead ends.

## Live public pages
- korvus_landing.html (/), pricing section anchor id pricing, prices inject from Stripe tokens, never hardcode.
- korvus_lodestone.html (/lodestone), korvus_signup.html, korvus_login.html, korvus_legal.html.

## Guide portfolio (/p/), 10 live, all sitemapped
- futures-tick-value-explained (shipped 10-29, X posted #328)
- futures-vs-stocks-small-accounts (shipped 10-29 #329, X posted #331)
- futures-rollover-explained (shipped 10-29 #332, X post filed #334)
- ES movers guide (X posted #327) plus 6 earlier guides, all in sitemap.
- In flight: ES trading hours and sessions guide, scribe drafting with verbatim CME hours.

## Standing gaps
- Landing page links none of the guides. Blocked until the exact CURRENT text of korvus_landing.html is in hand.
- New guides must bake related-links to sibling guides at the bottom, now part of every scribe brief.

## Rules that bit us
- One <title> per file, svg uses aria-label (HEALER LESSON in [[Patterns]]).
- Every outbound Korvus link carries UTM, standing infra since 10-26.
- Funnel target for all guides: free Observer signup at /signup. See [[Funnel]].