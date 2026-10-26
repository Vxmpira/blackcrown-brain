# Scout: From the latest korvus site audit confirm the exact repo

Date: 2026-10-25
Task: From the latest Korvus site audit, confirm the exact repo file path of the news terminal page and return its exact current visible body copy verbatim
For [[Corvid]].

**Finding: Cannot confirm. No site audit data was attached to this task, so I have no grounded source for the file path or the page's body copy.**

**Evidence:**
- The task context describes the naming convention (korvus_ prefix at repo root, homepage at `korvus:korvus_landing.html`) but does not include the audit itself or any file listing.
- Instruction was explicit: do not guess the path, only use what the audit lists. Nothing was listed, so I have zero confirmable paths beyond the homepage you already named.
- Returning body copy "verbatim" requires the actual page source or audit extract. Fabricating it would poison the CURRENT block in your content swap proposal, which defeats the purpose of a before/after diff.
- Reasoning from general knowledge only: the convention suggests a path like `korvus_news.html` or `korvus_terminal.html`, but this is inference, not audit data, and should not be filed.

**Recommended moves:**
1. Re-issue this task with the audit file listing (or the relevant audit section) attached so I can match the exact path.
2. If the audit is unavailable, pull the repo root directory listing directly and send me the korvus_ prefixed files; I'll identify the news terminal page from there.
3. Once the path is confirmed, send the raw HTML of that file and I'll extract the visible body text block verbatim for your CURRENT field.
