# Prospector: Map where visitors drop off before the korvus click

Date: 2026-10-29
Task: Map where visitors drop off before the Korvus click
For [[Herald]].

## Click Leak: Drop-Off Map (Korvus, 7 days)

**Baseline:** 40 visits, 2 clicks (5% visit-to-click), 0 signups. The quota is 50 Korvus signups, so the leak sits upstream of the first paying customer rung.

**Not instrumented yet:** I have no per-step data: no source breakdown, no scroll depth, no CTA impression count, no device split. Every hypothesis below depends on those numbers. The first move is a funnel event set, not a copy change.

## Likely Audience Arriving

Most likely: index futures traders who already know the category, arriving from Eclipse-X or brand-site referrals, plus a smaller tail of general AI or tech browsers who landed on the brand. The trader segment is the one that should click, so a 5% rate suggests the first screen is not making the trader's problem obvious fast enough.

I do not have the live homepage first-screen copy in this context, so I cannot quote what it promises. Pull the current hero text before the next review and check it against the three hypotheses.

## Three Hypotheses for the Click Leak

**H1: The first screen speaks to a general audience, not index futures traders.**
If the hero says "market intelligence" without naming session levels, index futures, or the trader's daily routine, traders scroll past and the curious tail bounces.
- **Test:** Compare click rate by UTM source (UTM tagging has been standing since 2026-10-26). Then run a hero variant that names the instrument and the 24/7 watch angle, and split traffic 50/50 for 14 days.
- **Target:** Trader-intent source click rate of 10% or higher, against the 5% baseline.

**H2: The CTA is not visible on phone-width screens before the visitor leaves.**
If the button sits below the fold or behind a long section on a phone, most mobile visitors never see a way forward.
- **Test:** Instrument CTA impression and scroll depth by device. If mobile CTA impressions are under half of desktop, move a CTA into the first screen on phone width and compare click rate across the next 14 days.
- **Target:** Mobile click rate within 70% of desktop, and CTA impression rate above 90% of visits.

**H3: The free path is unclear, so the click feels like a commitment.**
If the first screen leads with price or a paid tier and never says the Observer tier is free, visitors who want to look first do not click.
- **Test:** Add a single line to the hero that states the free Observer tier and what it includes. Keep prices out of hardcoded copy; Korvus landing prices inject server side from Stripe, so test the wording without dollar amounts. Run as a split against the current hero.
- **Target:** Hero CTA click rate up at least 2x against the control, measured over the same window.

## Recommended Next Moves

1. File a funnel event proposal for Regent: landing view, scroll depth at 50%, CTA impression, CTA click, split by device and UTM source. This makes H1 and H2 testable.
2. Run H3 copy as a split only after the event set is live, so the result is attributable.
3. Revisit this map after 14 days with the per-step numbers in hand.
