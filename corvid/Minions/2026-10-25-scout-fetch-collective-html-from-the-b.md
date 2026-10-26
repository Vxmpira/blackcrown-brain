# scout: Fetch collective.html from the brand site and return the full current body copy verbatim, headings and paragraphs in order, plus the current title and meta desc

For [[Corvid]], 2026-10-25.

# Scout Report: collective.html verbatim copy pull

**Finding:** Cannot complete as specified. I have no live fetch capability and no page source was included in the task, so I have zero exact strings to return. Verbatim means verbatim, and anything I produce without the source would be fabricated copy, which would poison the content swap proposal.

## Evidence

- No HTML, scrape output, CMS export, or cached snapshot of collective.html was attached to this task.
- I cannot access the brand site or any URL directly. This is a hard limit, not a judgment call.
- Reconstructing "likely" copy from general knowledge of BlackCrown messaging would violate the no-paraphrasing requirement and could cause Corvid to file a swap proposal against text that does not exist on the page. That risks a bad diff and a rejected proposal.
- Title tag and meta description are especially easy to get wrong from memory; these are exact-match fields in any swap filing.

## Recommended moves

1. **Resend the task with raw source attached.** A full `view-source` dump or a curl of collective.html pasted into the task body is enough. I will then extract title, meta desc, and body copy in document order, headings and paragraphs preserved exactly.
2. **If a scrape pipeline exists, route it first.** Have whatever fetch tooling Corvid uses pull the page and hand me the output. My job is extraction and structuring, not retrieval.
3. **Grab a timestamped snapshot for the proposal.** When the source is pulled, capture the fetch date alongside it. Content swap proposals are stronger when the "current state" is dated, in case the page changes between filing and review.

Standing by. Send the source and you will have the verbatim extraction back fast.
