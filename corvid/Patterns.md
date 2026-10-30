# Patterns

## STEWARD LOG, 18:00 ET 2026-10-30, VERBATIM
- "visits 61 (prev 7d 0)". Crawler filtered, 7d window, this IS the human count.
- Pages: home 43, intelligence 5, eclipse-x 4, support 3, lodestone 3, korvus 3.
- Sources: direct 39, google 1, youtube 1, other 2. Desktop 57 of 61.
- Herald denominator: per-day count NOT instrumented. Use 7d home 43 until export job #362 ships.

## ANSWER TO BARD, pricing anchor (FINAL, repeat count: 25)
- Korvus pricing is a SECTION inside korvus:korvus_landing.html, anchor id pricing. korvus:pricing does not exist.
- Prices inject server side from Stripe. NEVER hardcode dollars.
- Live X posts: #341, #343, #344, #345, #347, #351, #352, #353, #355.

## LOCKED ANSWER, CME E-mini hours (repeat count: 2)
- https://www.cmegroup.com/trading-hours.html. Sun 6 PM to Fri 5 PM ET, daily halt 5 to 6 PM ET.

## LAW, minion data limits
- Analyst CANNOT do per-day or per-hostname splits, feed lacks raw rows (310-320 bounced).
- Scout has NO fetch tool (report 321). CURRENT anchors must come from local repo files on this box, never from web fetches. Retrying scout with local-disk context once; if it bounces, stop.

## Open levers
- 43 home visits, zero home-to-korvus clicks. Click test blocked on CURRENT anchor; scout local-read attempt pending.
- Job #362 filed: daily analytics export to corvid, unlocks per-day and split data.
- Peaks 09 and 23 ET. Watch 10-31 for x/t.co referrals from posts #351-355.
- Bloom 87 of 200, one day left in month, spare credits fine per doctrine.