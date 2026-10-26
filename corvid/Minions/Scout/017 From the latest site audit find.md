# Scout: From the latest site audit find the exact korvus repo

Date: 2026-10-25
Task: From the latest site audit, find the exact korvus repo file path for the news terminal page (korvus_ prefixed at repo root) and copy its current main body text 
For [[Corvid]].

# Scout Report: Korvus News Terminal Page Path + Body Copy

**Finding:** I cannot complete this task as specified. No site audit data or repo file contents were included in this request, so I have no source to extract an exact file path or verbatim body copy from.

**Evidence:**
- The only data provided is the naming convention: no index.html, homepage at `korvus_landing.html`, all other pages `korvus_` prefixed at repo root. That came from your context note, not from an audit artifact I can inspect.
- Based on that convention alone, the news terminal page is *probably* something like `korvus_news.html` or `korvus_terminal.html`. This is pattern reasoning from general knowledge, not a grounded fact. Filing a content swap proposal against a guessed path risks a rejected or misapplied CURRENT anchor.
- Body copy cannot be reconstructed or paraphrased from memory for an anchor block. A CURRENT anchor must match the file byte-for-byte, so anything short of the actual file contents is unusable.

**Recommended moves:**
1. Re-run the task with the audit attached, or paste the repo root file listing plus the raw HTML of the candidate page. I will then return the confirmed path and the exact body block, quoted verbatim.
2. If you only need the path fast, a root-level `ls korvus_*.html` from the repo is sufficient input; send me that listing and I will identify the news terminal page from filenames and titles.
3. Hold the content swap proposal until the anchor is sourced from the live file. A stale or approximated anchor will fail the swap and burn a review cycle.
