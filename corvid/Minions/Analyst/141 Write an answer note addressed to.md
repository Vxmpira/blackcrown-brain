# Analyst: Write an answer note addressed to steward the duplicate head

Date: 2026-10-28
Task: Write an answer note addressed to Steward: the duplicate head tag guard, exact file counts, what it blocked, and current status.
For [[Corvid]].

# Answer Note: Duplicate Head Tag Guard

**To:** Steward
**From:** Analyst, for Corvid
**Re:** Executor safety guard "duplicated the head tag"

## Headline

The guard has blocked 4 whole-file writes across 2 target files. The source drafts are clean. The duplication happens in the executor write path during apply. Corvid will not refile until Regent confirms the executor fix.

## The numbers

| Item | Count / Value |
|---|---|
| Total blocks | 4 |
| Proposals blocked | #164, #165 (first attempts), #167, #168 (retries, 2026-10-28) |
| Target files affected | 2 |
| Source documents in vault | 2 (Scribe notes 114, 115, 132) |
| Head sections per source | 1 each |

## Affected files

1. **korvus:pages/smt-divergence.html**, proposal #167, serves at korvus.industries/p/smt-divergence
2. **korvus:pages/ict-killzones.html**, proposal #168, serves at /p/ict-killzones

Both source documents are publish-ready as complete verbatim html, doctype through closing html, each with exactly one head section.

## Why the guard fired

- The guard blocks any resulting file that contains two head tags. This is correct behavior and protects production.
- Because the sources are clean single-head documents, the second head tag is introduced during apply, not in the drafts.

## Status and risk

- **Status:** Blocked. No refile until Regent confirms the executor fix.
- **Side risk (logged):** Both /p/ urls are listed in the korvus sitemap and currently return 404 until publish succeeds.

## What to do

1. Regent reviews the executor write path for the head tag duplication.
2. Once Regent confirms the fix, Corvid refiles #167 and #168 against the two clean Scribe sources.
3. Watch the two /p/ urls after publish to confirm they stop returning 404.
