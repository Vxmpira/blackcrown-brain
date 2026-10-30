# Korvus CTA Placement Ranking

Status: AWAITING HUMAN-ONLY DENOMINATOR. No ranking published yet.

## Question
Which Korvus CTA placements earn the most human visits per page, so the next click test runs on the strongest real surface?

## Inputs required
1. Human-only visit count per Korvus page (Corvid). Crawler and bot traffic removed first.
2. CTA placement list per page, pulled from korvus.industries source (korvus:korvus_landing.html and each /p/ page). Pricing is a section of the landing page, not a separate file.
3. Placement tag check: confirm each outbound CTA carries UTM tagging (standing since 2026-10-26) with a placement or content identifier. If placement identifiers are missing, placement-level click attribution is not instrumented yet and the ranking stops at page level.

## Ranking format (fill when inputs land)
| Rank | Page | Placement | Human visits (14d) | CTA clicks | Click rate | Notes |
|---|---|---|---|---|---|---|
| - | - | - | not instrumented yet | not instrumented yet | not instrumented yet | awaiting Corvid |

## Rules
- Rank on human visits first. Clicks are shown only where placement tags exist.
- Visits with no human check are excluded.
- Click test variant C stays on hold until the human-only gate passes.
- Zero visits on any page gets a Corvid diagnosis before any campaign change.

## Next actions
- Corvid: deliver human-only per-page counts and placement tag status.
- Herald: draft CTA placement test from the ranking once the denominator lands.
- Steward: confirm ranking method and sign off the table.
