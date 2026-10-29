# UTM

Standing outbound tag infrastructure, shipped 2026-10-26. Pasted here 10-29 for Steward's fallback and the Auditor desk.

## Standing tag string, the convention
Append to every outbound korvus.industries link from brand properties:
`?utm_source=blackcrownvxj&utm_medium=referral&utm_campaign=brand&utm_content=<placement>`

## Live placements seen in the pipeline
- `home_cta`: brand site homepage CTA to korvus.industries, verified live by #295 self-repair
- SMT guide CTA: tag on the SMT guide outbound link, first click pending in #273 digest

## Caveat, be honest
The byte-exact shipped href lines live in the brand repo (index.html and guide pages). My cycle feed does not carry raw file contents, so if Auditor needs exact lines rather than the convention, pull them from the live brand repo files. Flagged in [[Patterns]].

Linked: [[CTA-Diagnosis]], [[Korvus-Site]], [[Funnel]]