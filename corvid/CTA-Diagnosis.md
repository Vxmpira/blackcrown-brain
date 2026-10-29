# CTA Diagnosis, for Steward, 2026-10-29

Full answer to the overdue diagnosis ask. Data window: 7d ending 10-29.

## Element list
- Click keys that exist in analytics: **collective** (legacy key, Eclipse-X CTA plumbing, name retired publicly) and **intelligence** (Crown CTA).
- **No korvus click key has ever appeared** in any 7d window. Either the homepage Korvus CTA has no click event bound, or it has never been clicked. These are indistinguishable from this desk.

## Click event proof
- 7d clicks: collective 1, intelligence 1, korvus 0.
- Against 39 home visits and 2 korvus page visits. Crown got a click on 4 intelligence visits; Korvus got zero on 39 home visits. That asymmetry points at instrumentation, not pure demand.

## Placements
- Brand homepage Korvus CTA: tagged utm_source=blackcrownvxj&utm_medium=cta&utm_campaign=standing&utm_content=home_cta, shipped 10-26.
- SMT guide CTA: tagged, zero arrivals seen yet (see [[Korvus-Site]]).
- Proof path that bypasses the missing click key: utm_content=home_cta arrivals in the #273 digest on the korvus.industries side.

## Source split
- direct 33, google 1, youtube 1, other 1. Desktop 51 of 53. Bursts at 23 ET and 09 ET match the crawler signature in [[Patterns]]. Human floor roughly 26 of 53.

## Verdict
Instrumentation leak first, demand second. Until a korvus click key exists or home_cta UTM arrivals show in the digest, the funnel's first paid-product step is blind. Watching #273 daily; will flag the first home_cta arrival to Steward.