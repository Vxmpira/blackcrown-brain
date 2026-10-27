# Prospector: Find why cold visitors leave the korvus homepage without clicking

Date: 2026-10-27
Task: Find why cold visitors leave the Korvus homepage without clicking
For [[Herald]].

## Why cold visitors leave the Korvus homepage without clicking

**Baseline:** 30 visits, 2 clicks in 7 days (6.7%). That is too small to separate hypotheses on its own. Treat the tests below as directional until traffic is larger. Scroll depth, time on page, and traffic source per visit are **not instrumented yet**. Filing that instrumentation should come before or alongside the first test.

### Hypothesis 1: The visitor cannot tell what Korvus is within five seconds

- **Evidence:** Korvus is a 24/7 market intelligence terminal for index futures traders, but a cold visitor may not map "terminal" and "intelligence" to a tool they can use tonight. The product's value (scored news, the Korvus read, LodeStone levels) lives below the fold or in feature detail, not in the hero line. Low click rate across 30 visits is consistent with a bounce before the value is understood.
- **Test:** Keep the layout, change only the hero primary CTA label from a generic action to a concrete one that names the outcome, such as "See today's scored market wire." Measure homepage visit-to-click rate against the 6.7% baseline over the same window length.

### Hypothesis 2: The first click asks for too much commitment

- **Evidence:** The only obvious conversion path is toward paid tiers. The price ladder is Operator at 9.99 a month or 79.99 a year, and the free Observer tier is a lower-commitment step. A cold trader who has not seen the product yet is being asked to evaluate money before evaluating value. Prices are server-injected, so visitors see the paid numbers as soon as they reach the pricing section.
- **Test:** Change the primary CTA to the free Observer entry (signup) and leave the Operator section as a secondary link. Measure the click rate on the primary CTA against baseline. Success is a meaningful lift in clicks, with signup completions tracked as the downstream metric toward the 50-signup quota.

### Hypothesis 3: No proof on the page, so trading-tool skepticism wins

- **Evidence:** Trading tools draw heavy skepticism, and the brand's standard is honesty over hype. The brand site's proof page is excluded from the sitemap until it has real content, which means there is no proof surface yet. The homepage likely asks for trust before showing anything concrete. The not-advice disclaimer is required, and it may be the most prominent text a cold visitor reads.
- **Test:** Add one secondary CTA beneath the hero, "See how a wire read is scored," that anchors to a section showing a sample scored wire. Label the sample clearly as **Illustration**. Measure total homepage click rate (primary plus secondary) against baseline, and split by which CTA was clicked.

### Recommended order

1. File instrumentation for scroll depth and traffic source. Without it, a failed test cannot be diagnosed.
2. Run Hypothesis 1's CTA copy test first. It is the cheapest change and tests the most basic failure, a visitor who does not understand the offer.
3. Run Hypothesis 2 or 3 next, depending on which result is still unexplained.

Each test is a homepage change, so it ships as a proposal through Regent for owner approval in #boardroom before it goes live.

**Rung moved:** first paying customer, and the 50 signup quota.
