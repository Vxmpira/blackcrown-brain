# Auditor: Prepare cta and click path audit checklist for the smt

Date: 2026-10-30
Task: Prepare CTA and click-path audit checklist for the SMT guide
For [[Steward]].

# CTA and Click-Path Audit: SMT Divergence Guide

**Target:** `pages/smt-divergence-for-beginners.html` (korvus.industries, serves at `/p/smt-divergence-for-beginners`)
**Trigger:** Run the moment Corvid pastes the complete HTML into the vault, before any proposal reaches the owner.
**Gate:** Pushes to main are production within about 2 minutes, so nothing merges until every Critical item passes.

## 1. Signup Link and UTM (Critical, revenue)

- [ ] Every Korvus signup CTA points to `/signup` on korvus.industries. Pass: no CTA targets `/upgrade`, `/terminal`, or `/account`, which are gated.
- [ ] Every outbound Korvus link carries the UTM tags already live under the 2026-10-26 standing infrastructure. Match the existing scheme exactly. Pass: no bare `/signup` links. Do not refile the tagging.
- [ ] Links to LodeStone point to `/lodestone`. Pass: no LodeStone CTA lands on the Korvus signup.
- [ ] No link targets `trading_news_terminal.html` or `korvus_promo_studio.html`. These are not served.
- [ ] Any Operator price shown reads 9.99 a month or 79.99 a year, annual first, with the computed savings label. Pass: no other figures. If a LodeStone price appears, it is 19.99 a month (TradingView) or 149 one time (Tradovate), and the two are never merged.
- [ ] Every internal and external href resolves. Pass: zero 404s on a crawl of the page.

## 2. Click-Path Logic (Critical, revenue)

- [ ] The primary CTA is above the first scroll on a 390px phone width.
- [ ] The path reads: guide, then one CTA to signup, with no more than one competing primary button per section.
- [ ] The Eclipse-X Discord link is secondary, not the main ask, and points to the open invite.
- [ ] Pass: the path from page load to a `/signup` click takes two clicks or fewer.

## 3. Mobile Layout Under 700px (Critical, shipped quality)

- [ ] Grids collapse to a single column under 700px.
- [ ] Headings use clamp(), and no heading overflows at 360px.
- [ ] Tables and figures span the full container with no horizontal scroll at 360px.
- [ ] Prose stays at reading width on desktop and fills the phone column without a narrow strip.
- [ ] Container sits near 1060px on desktop.
- [ ] Buttons are at least 44px tall and do not wrap mid-label.

## 4. Brand and Compliance (High)

- [ ] The inline crown SVG logo sits in the header.
- [ ] At least one real visual element exists (an SVG figure or data mock). Plain text walls fail.
- [ ] Any illustrative chart or sample data is labeled "Illustration."
- [ ] The not-advice disclaimer appears wherever a product claim or CTA appears.
- [ ] No promises of profit, no entry or exit instructions, no "signals" language.
- [ ] Zero em dashes in the document. No emoji in outbound copy.
- [ ] Background is not flat black. It uses soft CSS accent glows, a faint grid, and an edge vignette, with no images and no animation.

## 5. Serving and Discovery (Medium)

- [ ] The file sits in the korvus repo `pages/` folder and the slug is lowercase with hyphens only.
- [ ] The document is complete: doctype through the closing body tag, with nothing after it.
- [ ] No duplicate element ids.
- [ ] Decide whether the page enters sitemap.xml on korvus.industries. Log the decision either way.

## Verdict

- **Pass:** All Critical items pass. Medium or High misses go back to Corvid as a task with the one-line fix.
- **Fail:** Any Critical miss blocks the proposal. Corvid fixes it as a task. The owner is not asked to debug.
- **Report back to Steward:** List each failed item, its severity, and the one-line fix. Include the signup link as tested, with its UTM string.
