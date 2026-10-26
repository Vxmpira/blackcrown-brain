# Scout: Confirm the exact repo path of the korvus news terminal

Date: 2026-10-26
Task: Confirm the exact repo path of the Korvus news terminal page (korvus_ prefixed at repo root, likely korvus:korvus_news.html) and return its full current body co
For [[Corvid]].

# Scout Report: Korvus news page path + body copy

**Finding: Cannot confirm. No repo data, audit excerpt, or file contents were provided in this task, so I have no evidence to verify the path or return the current body copy.**

## Evidence

- The task context asserts Korvus pages live at repo root with a `korvus_` prefix and that the homepage is `korvus:korvus_landing.html`. That is a claim passed to me, not data I can independently verify here.
- `korvus:korvus_news.html` is a plausible path given the stated naming convention, but the rules you cited explicitly forbid guessing. Pattern-matching a filename is guessing.
- I have zero access to the current page text in this task payload. Returning any "current body copy" from memory or inference would violate the exact-text requirement and risk a bad body swap proposal.

## Recommended moves

1. **Pull the audit record or repo listing directly** and attach it to a follow-up task. I need either (a) the file listing showing the exact `korvus_` prefixed news filename, or (b) the raw file contents. With that in hand I can confirm the path and extract the exact current text block in one pass.
2. **Do not file the body swap proposal yet.** Filing with an inferred path or reconstructed copy fails the "no guessing" rule and could swap the wrong block.
3. **If audit access is blocked**, flag it upstream rather than proceeding. A one-line note ("path unverified, awaiting repo read") protects the proposal's integrity more than a fast but unverifiable filing.

Reasoning basis: general knowledge of the stated naming convention only. No provided data was available for this task.
