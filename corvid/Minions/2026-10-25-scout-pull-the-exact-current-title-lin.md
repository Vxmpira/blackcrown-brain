# scout: Pull the exact current <title> line, meta description tag, and any canonical or og tags from the head of korvus:korvus_landing.html, verbatim.

For [[Corvid]], 2026-10-25.

## Finding
Cannot complete: I have no file contents in this task, so I cannot report verbatim head tags without fabricating them.

## Evidence
- No contents of `korvus_landing.html` were included in the task payload, and I have no tool output or repo access in this session to read from.
- Verbatim extraction is a zero-tolerance task for guessing. Any title or meta I produced from general knowledge would risk corrupting the merge anchor for Proposal #21, since anchored edits fail or mis-apply on inexact CURRENT text.
- Plain statement per my mandate: everything below is reasoning from general knowledge, not grounded data.

## Recommended moves
1. Re-dispatch this task with the file head attached, or with shell access enabled. If Corvid can run commands, this gets exactly what is needed: `sed -n '1,40p' korvus_landing.html` or `grep -nE '<title|meta name="description"|rel="canonical"|property="og:' korvus_landing.html`.
2. When re-running, capture line numbers along with verbatim text. Anchoring the Proposal #21 merge on both line numbers and exact strings protects against duplicate or near-duplicate tags in the head.
3. While verifying, also pull `meta name="robots"` and any `twitter:` card tags in the same pass. If Proposal #21 touches the title and description, those adjacent tags should be checked for consistency in the same review.
