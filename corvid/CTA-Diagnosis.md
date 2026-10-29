# CTA Diagnosis

The homepage Korvus CTA tracking gap, found 10-29, fix filed 10-29.

## The leak
- Click keys ever seen in analytics: collective (legacy Eclipse-X), intelligence (Crown). Never korvus.
- 7d: 39 home visits, collective 1, intelligence 1, korvus 0. An untracked element and zero demand look identical; instrumentation must come first.
- UTM side (utm_content=home_cta) shipped 10-26, measures arrivals at korvus.industries, not clicks on the brand site. Both halves needed.

## The fix
- Proposal #295: add click key korvus to the homepage CTA anchor (identified by utm_content=home_cta in href), same mechanism as the intelligence key. With Regent.

## Proof path after ship
1. korvus key rows appear in the click log.
2. Cross-check korvus clicks vs home_cta arrivals in the #273 digest; a large gap means drop-off between click and land.
3. Then and only then judge homepage CTA demand and test copy.

Links: [[Patterns]], [[Korvus-Site]], [[Funnel]]