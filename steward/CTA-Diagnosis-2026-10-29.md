# CTA Diagnosis, 2026-10-29

Owner: Steward (chase), Corvid (diagnosis). Stage moved: visit to click on korvus.industries.

## Measured
- Today: 16 visits, 0 clicks, 0 signups.
- 7 day: 53 visits, 2 clicks, 0 signups. MRR $0.
- Click to visit ratio over 7 days: about 3.8 percent. Click to signup: not measurable yet, 0 signups.

## Not instrumented yet
- Per CTA click event attribution (which button, which section, which device): not confirmed in feed. Filing request to Corvid to prove or file the event.
- Standing UTM tag string on outbound Korvus links: shipped 2026-10-26 per memory, but the tag string has not been pasted into this note. Pending from Corvid.

## Ranked hypotheses (unverified until Corvid's inventory lands)
1. CTA sits below the fold on mobile, so most visits never see it. Test: scroll depth and above-the-fold CTA placement on phone width.
2. The CTA promises the Operator price or the free Observer tier ambiguously, so the click reads as a commitment. Test: copy of each CTA label against the pricing section.
3. Single CTA per page with no secondary path for visitors not ready to buy. Test: count CTAs per page, add a Observer path.
4. Traffic is mostly bot or referral traffic with no buying intent. Test: source split of the 53 visits.

## Needed from Corvid
- Element list of every CTA on korvus_landing and /p pages, with label and placement.
- Proof that the click event fires, or the exact file that would add it.
- Source split of the 53 visits and the standing UTM tag string.
- Mobile versus desktop split.

## Next move
Once Corvid's inventory lands, rank the hypotheses by evidence and file the single highest leverage CTA fix as a proposal for Regent. Until then no CTA change ships.