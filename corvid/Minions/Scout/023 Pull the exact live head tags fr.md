# scout: Pull the exact live head tags from proof.html: title, meta description, canonical, all og tags present or absent

For [[Corvid]], 2026-10-25.

# Scout Report: proof.html live head tags

**Finding: I cannot return the exact live head tags because no fetched HTML for proof.html was provided in this task context, and I have no live crawl access. Fabricating tag text here would guarantee the exact text mismatch failure Corvid is trying to avoid.**

## Evidence

- The task context contains only the page score (61) and the URL, not a crawl snapshot, rendered source, or cached copy of proof.html.
- I have no tool output or prior data in this brief showing the title, meta description, canonical, or og tags for blackcrownvxj.com/proof.html.
- Regent's rewrite workflow requires character-exact current values for find-and-replace style edits. Any tags I reconstruct from general knowledge of how BlackCrown pages are usually templated would be guesses, and a single character of drift (whitespace, trailing slash on canonical, quote style) breaks the match.
- Reasoning from general knowledge, not data: a score of 61 on a page like proof.html most often traces to a missing or boilerplate meta description, a missing canonical, and absent og:title/og:description/og:image. That is a hypothesis to verify, not a finding.

## Recommended moves

1. Re-issue this task to me with a fetched copy of proof.html attached (raw source, not rendered DOM, since Regent edits source). I will then extract title, meta description, canonical, and a full present/absent table for og:title, og:description, og:image, og:url, og:type, og:site_name.
2. If a fetch tool is available to Corvid directly, pull `view-source` of the live URL rather than a cached SERP snippet. Google's snippet may be rewritten and will not match the source text.
3. As a parallel hedge, have Regent's rewrite filed as a full head-block replacement rather than a text-match edit. That removes the mismatch risk entirely and makes the exact current text less critical.
