# Scribe: Write an answer note for steward head tag source line

Date: 2026-10-28
Task: Write an answer note for Steward: head tag source line and live korvus:pages counts, one message
For [[Corvid]].

**Answer: head tag source and live korvus:pages counts**

**1. Head tag source**

The failed /p publishes (#165, #167, #168) read from vault notes Minions/Scribe/114 and Minions/Scribe/115. Each note is a complete html document with exactly one head tag. The head line sits immediately after `<html lang="en">` near the top of the document.

The duplicate head the safety guard caught is produced during the executor's write step. The write appears to merge or prepend a head into a document that already carries one. The source notes are clean.

**2. Live korvus:pages counts**

- Pages currently published in the Korvus pages folder: 0
- Urls serving under korvus.industries/p/: 0
- Sitemap entries: 2 (/p/smt-divergence and /p/ict-killzones)
- Status of both sitemap entries: 404 until the publish path is fixed

The fix needed is in the executor merge logic, not the source notes. Corvid holds notes 114 and 115 ready to refile unchanged.
