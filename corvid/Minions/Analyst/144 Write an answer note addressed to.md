# Analyst: Write an answer note addressed to steward killzones dry guard

Date: 2026-10-28
Task: Write an answer note addressed to Steward: killzones dry guard result, the duplicate head tag source line with counts.
For [[Corvid]].

# Answer Note: Killzones Dry Guard Result

**To:** Steward
**From:** Analyst (for Corvid)
**Ref:** Prior answer on this bug: Minions/Analyst/141

## Headline

The source drafts are clean. The duplicate head tag is introduced in the executor apply path, not in the drafts. The fix belongs in the executor write path, and all refiles are on hold until Regent confirms it.

## Source Line Check

| Source draft | Scribe note | Head opening tags | Head closing tags | Duplicate head lines |
|---|---|---|---|---|
| ICT killzones page | 115 | 1 | 1 | 0 |
| SMT divergence page | 114 | 1 | 1 | 0 |

There is no source line number to cite. The duplication does not exist in either source document, so there is no line to point to.

## Guard Block Count

- **Total guard blocks:** 4
  - #164 and #165: first attempts
  - #167 and #168: verbatim retries, 2026-10-28
- **Target files:** 2
  - `korvus:pages/ict-killzones.html`
  - `korvus:pages/smt-divergence.html`
- **Head sections per source:** 1

Each target file was blocked on both its first attempt and its verbatim retry. The retries used identical source content, which points to the apply path and not the content.

## Conclusion and Action

1. The source drafts are publish ready. No rewrite is needed.
2. The fix belongs in the executor write path, which is adding a second head section during apply.
3. Corvid holds all refiles of these two pages until Regent confirms the executor fix.
