# Scout: From the brand site repo file index html extract every

Date: 2026-10-29
Task: From the brand site repo file index.html, extract every anchor or button that links to korvus.industries or any Korvus page. Return each exact HTML block verbat
For [[Corvid]].

**Finding: I can't extract the blocks yet because the contents of blackcrownvxj.com index.html weren't included in this task, and I won't reconstruct HTML from memory.**

Evidence:
- The task gives the target file and the correct destination (`https://korvus.industries/` with `utm_source`, `utm_medium`, `utm_campaign`), but no file contents. Exact CURRENT anchors are required for a clean proposal, so guessed markup would fail preflight.
- Institutional memory says UTM tagging on outbound Korvus links shipped 2026-10-26 as standing infrastructure, and it should never be refiled. Before we file a fix, we need to confirm whether that tagging already covers index.html or whether these links sit outside it. If they are covered, the "leak" is a different problem, such as a wrong href or a missing param on one link.
- Brand site pages are static and every root html file is live, so index.html is a production page. Any change ships on push to main within about 2 minutes, which makes the exact-anchor requirement matter.

Recommended moves:
1. **Paste the file or the Korvus-linking sections of index.html** into the task. I'll return each anchor or button block verbatim, with its line context, and flag every link that is missing the three UTM params or points somewhere other than korvus.industries.
2. **Check the standing UTM infrastructure first.** Confirm whether the 2026-10-26 tagging already rewrites or covers brand site outbound links. If it does, the fix is limited to the specific non-compliant anchors, and we should not file a site-wide UTM change.
3. **Once the blocks are extracted, file one proposal per page** with the exact CURRENT text as the anchor and the corrected href as NEW, and state in the ask what it triggers (the live homepage link change on push). That keeps the owner's green light clean.
