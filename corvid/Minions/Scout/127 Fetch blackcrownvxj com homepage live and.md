# Scout: Fetch blackcrownvxj com homepage live and report the exact hero

Date: 2026-10-28
Task: Fetch blackcrownvxj.com homepage live and report the exact hero headline, subheadline, every CTA button text, and each CTA href in order of appearance
For [[Corvid]].

**Finding: I could not fetch blackcrownvxj.com live, so I have no verbatim hero, subheadline, or CTA text to report.**

- **Evidence:** My toolset here has no web fetch or repo read, so I have not seen the page as served. Any headline or href I wrote now would be guessed, and a guessed CURRENT anchor would fail executor preflight.
- **Evidence:** Institutional memory says blackcrownvxj.com is static, and every root html file in its repo is a live page. The homepage is probably index.html, but I have not confirmed that, so the file name needs checking before anyone files against it.
- **Evidence:** The 28 of 33 visits with zero outbound clicks to korvus.industries is the reported figure. I have not verified it. Outbound Korvus links carry UTM tags (shipped 2026-10-26), so click attribution from the brand site should be checkable there. I have not checked it.
- **Evidence:** The copy and link targets are needed in exact form because a content edit's CURRENT anchors must match character for character.

**Recommended moves**

1. **Pull the raw source, not a summary.** Have a desk with repo read access return the full text of the homepage file (index.html, if that is the live root) with the hero, subheadline, and every `<a>` element with its href, in document order. That gives the exact anchors the Korvus-first edit needs.
2. **Confirm the click number before filing.** Check the UTM-tagged Korvus link data for brand-site referrals over the same 7 days. If the zero-click figure holds, the edit is justified. If clicks exist but are under-attributed, fix the tracking first. Either way the number should be instrumented, not assumed.
3. **Draft the Korvus-first edit only after step 1 returns.** Keep the Korvus CTA's copy consistent with the landing and the 9.99 Operator ladder, with no hardcoded prices, and the not-advice disclaimer on product claims. Route the proposal to Regent for review, then the owner's green light in #boardroom.
