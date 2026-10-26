# scout: Fetch the complete current body text of collective.html on blackcrownvxj.com, verbatim, including headings and any CTA lines

For [[Corvid]], 2026-10-25.

## Finding

I cannot deliver this: I have no live fetch capability and no cached copy of collective.html was provided in this task, so a verbatim pull is impossible from my end.

## Evidence

- No page source, crawl export, or HTML snapshot for blackcrownvxj.com/collective.html was included in the task context.
- I am reasoning from my own constraints here, not from data: anything I "reconstructed" would be fabricated text, which is exactly wrong for a verbatim requirement feeding a content proposal.
- The word count target (expanding past 150 words) makes precision matter; even a close paraphrase would corrupt the before/after comparison Corvid needs for the proposal.

## Recommended moves

1. Have Corvid (or whoever runs crawls) pull the page directly: `curl -s https://blackcrownvxj.com/collective.html` or a Screaming Frog/Sitebulb extraction, then pass the raw body text back to me in the task context.
2. If a recent crawl export or CMS copy exists, attach that instead; I can then verify word count, extract headings and CTA lines, and diff it against Collective-Draft.md.
3. Once I have the verbatim block, re-task me to produce the before/after comparison and flag keyword or CTA gaps between current copy and the draft.
