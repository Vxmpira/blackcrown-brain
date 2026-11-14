# Auditor: Rule crier observer post sentences against live copy

Date: 2026-11-14
Task: Rule Crier Observer post sentences against live copy
For [[Steward]].

## Auditor findings: Crier Observer post ruling

**Ruling status: blocked. No sentence can be ruled yet.**

**1. Critical: the source text is missing from this task.** The Crier draft sentences are not attached, Community.md excerpts are not attached, and the Korvus landing source read is still pending. A PASS or FAIL issued now would rest on memory, which the task rules out. Ruling anything today would be the kind of guess that burns trust.
- **Fix:** Steward attaches the Crier draft verbatim, one sentence per line, and the exact released lines from Community.md and the Observer section of korvus:korvus_landing.html. Rule only from quoted lines.

**2. High: three of the four draft claims are product facts that the live copy has to support.** "ES and NQ overnight coverage," "Globex range," and "Observer includes core feed" are specific feature claims about the free tier. Observer is the free tier, and the landing copy is the only authority on what it includes.
- **Fix:** For each claim, find the literal live line that names the instrument, the session, or the feed. If the live copy says less, or does not name it, that sentence FAILs and the post is rewritten to match the live copy.

**3. High: the publish path has no gate.** X posts go out directly from the server with the brand account's keys and are live on send. If Crier files before the landing read lands, the post can outrun verification.
- **Fix:** Hold the Crier post until every sentence has a PASS with a quoted line. Any single FAIL blocks the whole post, not just the sentence.

**4. Medium: the draft has not been checked against house standards.** Before any ruling, confirm no em dashes, no emoji, no profit or advice language, no hype, and the not-advice disclaimer on any product claim.
- **Fix:** Add these as a second pass after the factual rulings, so the output is checked for both accuracy and voice.

**5. Low: the ruling format needs a fixed shape so Steward can act on it.**
- **Fix:** Each sentence gets one line: `[PASS|FAIL] "draft sentence" | live: "quoted line" (source file)`. A FAIL also carries the replacement sentence drawn from live copy.

**Next step:** Steward re-files this task with the three inputs above. Ruling follows immediately after.
