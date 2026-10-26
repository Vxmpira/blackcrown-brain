# Auditor: Audit the three live sites for broken signup paths dead

Date: 2026-10-25
Task: Audit the three live sites for broken signup paths, dead links, and missing CTAs from homepage to paid tier, report per site with page names
For [[Steward]].

# Audit Status: Blocked, With Workaround

**Blocker:** I cannot load live URLs. I have no browser access, so I cannot click through korvus.industries, blackcrown-intelligence.com, or blackcrownvxj.com directly. Reporting fake findings would be worse than no findings.

**Fix:** Paste me one of the following per site and I audit same-session:
- Homepage HTML or full page text, plus the signup/pricing page content
- Screenshots of homepage, pricing, and checkout
- Sitemap or list of pages with their links and CTAs

## What I Can Deliver Now: The Funnel Checklist To Run Yourself

Ranked by how often each kills conversions at 0 subscribers:

**1. Checkout actually completes**
Test a real purchase on Operator ($9.99) and Pro ($49.99) with a live card in Stripe test or live mode. Most common zero-subscriber cause is a payment processor misconfigured, in test mode, or never connected.
*Fix: Run one end-to-end purchase per site today, refund yourself after.*

**2. CTA exists above the fold on the homepage**
Each homepage needs a visible button leading to pricing or signup without scrolling. No CTA means traffic bounces regardless of volume.
*Fix: One primary button per homepage, verb plus outcome, linking straight to pricing.*

**3. Click path length homepage to payment**
Count clicks from landing to entering card details. More than 3 clicks or any dead end (link to a 404, a form that submits nowhere) kills the funnel.
*Fix: Map the path per site, cut to homepage, pricing, checkout.*

**4. Signup form submission works**
Submit the form with a test email. Check for confirmation page, confirmation email, and that the record lands somewhere (database, Stripe customer, mailing list).
*Fix: Test submit on all three sites, verify the record exists on the backend.*

**5. Dead link sweep**
Free tools (Broken Link Checker, Screaming Frog free tier) crawl each domain in minutes. You do not need me for this part.
*Fix: Run a crawler per domain, paste results here, I will prioritize repairs.*

**6. blackcrownvxj.com has no stated paid tier**
Context lists prices for two sites only. If the third has no product attached, it is brand overhead, not a funnel.
*Fix: Confirm its purpose, either add a tier or make it funnel traffic to the other two.*

## One Flag For Steward

Three sites, two paid products, zero subscribers suggests the problem may be upstream of broken links: do we have any traffic data at all? If analytics shows under ~100 visitors/month per site, a perfect funnel still yields zero. Audit the funnel, yes, but pull visitor counts in parallel so we are not polishing doors nobody walks past.

**Next step:** Send page content or crawler output for site one. I turn it around as a proper per-page report.
