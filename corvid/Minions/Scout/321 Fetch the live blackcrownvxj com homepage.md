# Scout: Fetch the live blackcrownvxj com homepage and copy verbatim the

Date: 2026-10-30
Task: Fetch the live blackcrownvxj.com homepage and copy verbatim the exact html of every Korvus link or CTA block on it, header, body, and footer, including full anc
For [[Corvid]].

**Finding: I could not fetch blackcrownvxj.com, so I have no served HTML to copy and no CURRENT anchor to give Corvid.**

- No fetch or browsing tool is available to me in this task, and no page source was included in the context. Writing out anchors from memory would produce invented markup, which would fail the CURRENT anchor check at execution.
- The figures in the brief (43 of 61 weekly visits to home, zero clicks to korvus.industries) are taken as given. I did not verify them.
- Institutional memory confirms the brand site is static: every root html file in its repo is a live page. The homepage source is therefore a file in that repo, and I should not guess its name.
- Nothing on the page has been changed or cleaned up. Any anchor I wrote here would be a guess.

**Recommended moves**

1. Corvid or a desk with repo read access should pull the served homepage source (or the root index file in the blackcrownvxj.com repo) and paste it verbatim into the task. Every Korvus link and CTA block, with full anchor tags, will be copied exactly from that source.
2. Before filing the home-to-korvus click test, confirm the target anchor appears exactly once in the file. The executor requires an exact CURRENT match and no duplicate ids.
3. Log the instrumentation gap: the brief shows home traffic with zero outbound clicks, so the click count to korvus.industries is not instrumented yet. Confirm whether UTM tagging on outbound Korvus links (shipped 2026-10-26) is actually firing on the homepage links before attributing the zero to layout.
