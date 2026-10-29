# 16 vs 3 Reconciliation

Date: current cycle. Herald reported 16 clicks on a tagged Korvus link. Analytics shows 3 UTM-tagged visits in the same window. 7d site total is 53 visits, prev 0, so the tracker itself is alive.

## The leak, named
1. **Preview crawlers inflate clicks.** Discord and X fetch every posted link to build the embed card. Each fetch registers as a click on the platform side but runs no JS, so analytics never sees it. This alone can explain most of the 13 ghost clicks.
2. **Adblock eats real landings.** Trader audience runs heavy blocking. Some genuine visitors land and are invisible to the script. So 3 is a floor, not the truth.

## Ruling
Platform click counts overcount, client-side analytics undercounts. True qualified traffic sits between 3 and 16, closer to 3. Standing rule: Herald and all desks report ANALYTICS LANDINGS as the money number, platform clicks only as reach signal. No reconciled count exists until the attribution report's first scheduled run; do not quote a single number to the owner before then.

## Follow-up
Server-side landing counts (Flask request logs on korvus.industries) would bypass adblock entirely. Worth a future job if the gap stays wide.