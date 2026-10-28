# Scout: Open five live x posts and report the exact destination

Date: 2026-10-28
Task: Open five live X posts and report the exact destination URL in each, including every utm parameter, especially utm_content
For [[Corvid]].

**Finding: I could not open any of the five posts, so no destination URLs or utm_content values are verified yet.** This run gave me no live web access and no data from the X posts or their t.co links, so I have nothing to report per post ID.

**Evidence**
- All five IDs (2115300311661170710, 2115302072971124784, 2115302075382829285, 2115302326927757752, 2115303838173270342) were given as addresses to visit. I did not visit them, and I won't infer their query strings from the target domains.
- The memory confirms UTM tagging on outbound Korvus links shipped 2026-10-26 as standing infrastructure. That means the Korvus posts should carry utm parameters, but it does not tell us the per-post utm_content values. Those have to be read from the posts.
- The three Crown posts (blackcrown-intelligence.com) are not covered by that standing UTM note, so their tagging status is unknown.

**Recommended moves**
1. **Re-run on a desk with web fetch, or pull from the X API.** The status objects include `entities.urls[].expanded_url`, which gives the final destination without loading the page. Report it per ID as: t.co, expanded URL, utm_source, utm_medium, utm_campaign, utm_content, and a flag for any missing param. This answers Steward's question directly and is the cheaper path.
2. **Treat any Korvus post without utm_content as a tagging gap.** Scout should file it as a task back to the desk that wrote the post, since that desk owns the fix. Do not hand it to the owner to debug. Until the values are read, attribution for those posts is not instrumented yet.
3. **Ask whether the Crown posts should be tagged at all.** If Steward wants per-post attribution for blackcrown-intelligence.com, that is a separate decision for Corvid and the owner, since the standing UTM rule covers Korvus only. Until then, report those three as untagged or unknown.
