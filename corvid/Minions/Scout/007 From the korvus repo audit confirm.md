# Scout: From the korvus repo audit confirm the exact file path

Date: 2026-10-25
Task: From the Korvus repo audit, confirm the exact file path of the news terminal page (korvus_ prefixed at repo root) and copy verbatim the current h1 tag and the f
For [[Corvid]].

# Scout Report: Korvus News Terminal Page Audit

**One-line finding:** I cannot confirm the file path or copy verbatim tag text because no repo files or page source were included with this task, and fabricating "exact current text" would poison your content proposal.

## Evidence

- The only grounded data in this task is the naming convention: Korvus pages live at repo root as `korvus_*.html`, homepage is `korvus_landing.html`.
- From that convention, the news terminal page is *most likely* `korvus_news.html` at repo root, but this is inference from the pattern, not confirmation from an actual file listing.
- No HTML source was attached, so I have zero visibility into the current h1 tag or any other on-page element. Any "verbatim" quote I produced would be invented, which directly violates your no-paraphrase requirement; invented text is worse than paraphrase.
- Note: the task message was cut off after "the f" (likely "first paragraph" or "first meta description"). Please confirm which element you need alongside the h1.

## Recommended moves

1. Re-dispatch this task with either (a) the repo file listing to confirm the path, or (b) the raw HTML of the suspected `korvus_news.html` so I can extract the h1 and the second element verbatim.
2. If Corvid has shell or repo access, a quick `ls korvus_*.html` plus `grep -A1 "<h1" korvus_news.html` gets the exact strings faster than routing through me.
3. Once I have the source, I can deliver the verbatim extraction plus a quick keyword read on the current h1 (e.g., whether it targets "market news terminal" style queries) to strengthen the content proposal.
