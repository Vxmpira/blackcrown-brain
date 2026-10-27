# Prospector: List three testable hypotheses for the 6 7 percent click

Date: 2026-10-27
Task: List three testable hypotheses for the 6.7 percent click leak
For [[Herald]].

## The 6.7% click leak: three testable hypotheses

**Sample check:** 2 clicks from 30 visits is too small to call a leak. A Wilson 95% interval runs about 2% to 21%, so the true rate could be near zero or near 20%. The brief's 0 to 19% is slightly off; the upper bound is closer to 21%. Any hypothesis below should be tested against a larger window before anyone changes the page.

**No landing text was provided, so every claim about page content below is unverified.**

### H1: The offer is not visible above the fold on mobile
- **Claim (unverified):** Visitors on phones never reach the Operator pricing section, which sits lower on the Korvus landing page.
- **Why plausible:** Pricing prices inject server side, so the block may be heavier or later on mobile. Unverified.
- **Test:** Split the 30 visits by device type. If nearly all visits are mobile and clicks cluster on desktop, H1 holds.
- **Shows in:** Visits to `/` (the Korvus landing) tagged with the Korvus `utm_campaign` for this source, split by device.
- **Kill condition:** Device split is roughly even, or mobile clicks match desktop clicks.

### H2: Traffic arrives on a path whose intent does not match the Korvus offer
- **Claim (unverified):** Some visitors land on `/legal` or `/login` instead of `/`, so they never see a path to sign up.
- **Why plausible:** Public URLs are `/`, `/lodestone`, `/signup`, `/login`, and `/legal`. A link pointing to a secondary path would produce visits with no conversion route.
- **Test:** Break the 30 visits down by landing path. If a large share lands on `/login`, `/legal`, or `/lodestone` with no onward click, the mismatch is the leak.
- **Shows in:** Landing path per `utm_campaign` for the source. Requires a landing-path breakdown; if the per-click job does not expose it, that is **not instrumented yet**.
- **Kill condition:** Nearly all visits land on `/` and the click gap persists.

### H3: Some clicks are not being counted
- **Claim:** The per-click UTM job undercounts. Real clicks happen, but the job misses some, so 2 is a floor, not the truth.
- **Why plausible:** Outbound link handling (new tab, blocked popups, in-app browsers) can drop events. This is a measurement hypothesis, not a page one.
- **Test:** Compare clicks in the per-click job against server hits to `/signup` carrying the same `utm_campaign` over the same 7 days. If `/signup` shows more tagged hits than the job counted, the leak is partly a counting gap.
- **Shows in:** `/signup` hits with the Korvus UTM value versus the per-click job total for the same window.
- **Kill condition:** The two counts match. Then the leak is real and H1 or H2 is the place to look.

### Recommended order
1. Run H3 first. It is cheap, and if it is true, the other numbers are wrong.
2. If H3 holds up, run H2 with a landing-path breakdown.
3. Run H1 only after the device split is confirmed, and verify the page layout before drawing any conclusion about it.
