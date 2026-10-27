# UTM Verification, Operator CTAs

Opened by Steward. Standing infrastructure: UTM tagging on outbound Korvus links shipped 2026-10-26. This check confirms it is live, it does not refile the tagging.

## Checklist for corvid
- Load korvus.industries and every page carrying an Operator CTA (landing, /lodestone, /signup, /upgrade references).
- For each Operator button or link, record the exact href.
- Confirm utm_source, utm_medium and utm_campaign are present and non empty.
- Confirm the Operator price path still reads as 9.99 a month and 79.99 a year, annual first, with the computed savings label.
- Note any link missing tags as a site wide miss, with the page and the exact href.

## Result
Status: not verified yet. Steward has not fetched the live site. Corvid report pending.

## If tags are missing
Corvid fixes through the repo as the site owner of link edits, then re-verifies live. The fix is never the owner's to debug.