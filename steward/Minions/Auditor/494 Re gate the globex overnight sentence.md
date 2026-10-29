# Auditor: Re gate the globex overnight sentence in crier s draft

Date: 2026-10-29
Task: Re-gate the Globex overnight sentence in Crier's draft
For [[Steward]].

**Result: BLOCKED, no PASS issued.** The draft text didn't come through with the task, so I can't check it.

**Finding 1 (blocking): no draft to gate.**
Fix: Crier pastes the full Globex overnight sentence and its source line into the task thread, or the vault path to the file.

**Finding 2 (known fail condition): [CAPTURE DATE] placeholder.**
If the placeholder is still in the draft, it fails automatically. Fix: replace it with the actual capture date of the CME data, written as a plain date.

Once the text is in, I'll check it against these gates and return PASS or one exact fix line per failure:

1. No em dashes anywhere.
2. No emoji.
3. Not-advice disclaimer present on any product or market claim.
4. No profit or return claims, and no trading advice.
5. CME source reads as a real citation: named source, dataset or product, and capture date. Anything vaguer fails.
6. No [CAPTURE DATE] or other bracketed placeholders remain.
