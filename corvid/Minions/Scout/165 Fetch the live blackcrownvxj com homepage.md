# Scout: Fetch the live blackcrownvxj com homepage and report the exact

Date: 2026-10-28
Task: Fetch the live blackcrownvxj.com homepage and report the exact verbatim hero headline, subhead, and every CTA button text and href, copied character for charact
For [[Corvid]].

**Finding: I could not fetch the live homepage, so I have no verbatim copy to report. Nothing below is copied from the page.**

- **Blocked:** This run has no web fetch or repo read tool. Any headline, subhead, or CTA text I wrote here would be invented, and Corvid would file an edit anchored to fake text. That fails the exact-anchor requirement.
- **Likely cause of zero exit clicks:** The 28 of 33 home visits and zero korvus.industries exits may mean the homepage has no outbound Korvus link at all, not that a link exists and nobody clicks it. Confirm this first. If the source contains no `href` to korvus.industries, the fix is adding one, not strengthening one.
- **Anchor rule:** Memory says blackcrownvxj.com is static and every root html file is a live page. The homepage file name is not confirmed in memory, and home.html does not exist, so I will not guess it.
- **Outbound links:** UTM tagging on outbound Korvus links is standing infrastructure (shipped 2026-10-26). Any new Korvus CTA href should carry the existing UTM pattern. Do not refile that work.

**Recommended moves**

1. **Pull the source.** Ask a desk or the owner's tooling to return the full raw contents of the homepage file from the blackcrownvxj repo, plus a grep for `korvus.industries` across all root html files. That output gives Corvid the exact anchors. Route it through a task so the fetch is recorded, not run from memory.
2. **Confirm the link gap before editing.** Use the grep result to decide between "add a new CTA block" and "change an existing href." If the homepage already links to Korvus and still gets zero exits, the problem is placement or copy, and that changes the proposal.
3. **Mark the measurement gap.** Exit clicks from brand to Korvus are only meaningful if the UTM-tagged links are counted. If the 7d zero came from a page with no links, note that the metric was reading an empty surface. Until a click counter exists on that CTA, say "not instrumented yet" in the proposal and file the tracking job alongside the copy edit.
