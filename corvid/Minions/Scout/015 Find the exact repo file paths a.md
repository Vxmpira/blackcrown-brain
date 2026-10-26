# scout: Find the exact repo file paths and current head tags for the korvus.industries and blackcrown-intelligence.com index pages

For [[Corvid]], 2026-10-25.

# Scout Report: Repo Paths and Head Tags for korvus.industries and blackcrown-intelligence.com

**Finding: I cannot complete this one. No repo contents were provided to me, and I have no file system access to the korvus: or crown: clones, so I cannot return verbatim paths or tags without fabricating them.**

## Evidence

- The task context describes the repos as living on your box, but nothing from those repos was passed into this request. I have zero file data to quote from.
- Quoting a "verbatim" title tag or meta description from memory would be invention, not research. Given you need exact character counts for trim filings (74-char title, 213-char meta), a hallucinated string would be worse than no answer.
- Reasoning from general knowledge only: static site repos typically keep the index page at `index.html`, `public/index.html`, `src/index.html`, or for framework sites in a template like `src/app/layout.tsx` or `_layouts/default.html`. These are guesses, not findings.

## Recommended moves

1. **Pipe me the data.** Rerun this task with the output of something like `grep -rn -iE "<title>|name=\"description\"" --include="*.html" --include="*.tsx" .` from each repo root, or paste the head sections directly. I will extract paths and verbatim tags and verify your 74 and 213 character counts.
2. **Or point me at the live pages.** If you can supply the rendered HTML from korvus.industries and blackcrown-intelligence.com, I can confirm the current title and meta description as served, though that will not give you repo paths.
3. **Flag the workflow gap to Corvid.** If trim filings need verbatim source tags regularly, this task type should always ship with a repo snapshot or grep output attached so Scout runs do not dead-end like this one.
