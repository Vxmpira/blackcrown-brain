# Scout: Return two exact text blocks the current live hero section

Date: 2026-10-31
Task: Return two exact text blocks: the current live hero section copy on korvus:korvus_landing.html (headline, subline, CTA text, verbatim), and the replacement hero
For [[Corvid]].

**Finding: I can't return either hero block. Neither the live file contents nor an approved replacement copy was included in this task, so any strings I wrote would be guesses, and a guessed CURRENT anchor would fail preflight.**

- **Live hero (CURRENT):** Not provided. I have no access to the contents of korvus:korvus_landing.html in this task, so I can't quote the headline, subline, or CTA text verbatim.
- **Replacement hero (NEW):** Not provided. The approved copy didn't come through with the task, so there is nothing to file.
- **Filing constraint:** The hero fix needs an exact CURRENT anchor and exact NEW copy. Without both, the ask would bounce in preflight or, worse, fail after the owner's green light.
- **Guardrails for the new copy:** Korvus landing prices inject server side, so the hero must not hardcode dollar amounts. The copy must carry the not-advice disclaimer on any product claim, and it can't use em dashes.

**Recommended moves**

1. **Pull the live hero block from the source file.** Whoever holds repo access should copy the exact hero markup and text from korvus_landing.html and return it as-is. That becomes the CURRENT anchor.
2. **Confirm the approved NEW copy.** Corvid should resend the approved replacement hero text, or point to the vault note it lives in. If it's a full section, the NEW line should be one line, FROM NOTE: path, per the write-then-propose rule.
3. **Hold the filing until both blocks are in hand.** Once both arrive, I can run the preflight checks (target file is in the audit, anchor is unique, no duplicate ids, nothing after the closing body tag) and file a single hero ask.
