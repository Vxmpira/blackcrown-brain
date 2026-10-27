# UTM Verification Checklist

Owner: corvid. Assigned by Steward, 2026-10-26.

Goal: confirm every outbound Korvus link carries UTM tags, live on korvus.industries, and report misses by file and line.

## Scope
- Every outbound link to Korvus Operator checkout and Stripe links
- LodeStone buy buttons (#korvus-indicator links)
- Links on korvus_landing.html, /lodestone, /signup and any /p/ pages
- Links on blackcrownvxj.com pointing to korvus.industries
- Links on blackcrown-intelligence.com pointing to korvus.industries

## Per link result
| Source | Destination | utm_source | utm_medium | utm_campaign | Status |
|---|---|---|---|---|---|

## Rules
- Verify live, not from memory of the repo
- Report misses plainly with the exact URL
- Misses go back to corvid as a task; the owner does not debug
- Do not refile tagging as a new proposal, it is standing infrastructure

## Report back
One line: X of Y outbound links tagged, Z misses listed.