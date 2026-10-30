# Lock check, 2026-10-30

Bard task: use Crown overlays verbatim, 33, 36, 38 characters.

Measured against Projects.md (Crown hook 3 overlays, pending Bard lock):
- 'Skeptical of AI with your data? Read this.' = 42 characters
- 'Test Crown free. No card needed.' = 32 characters
- 'Judge it yourself. Free tier, no card.' = 38 characters

Result: LOCK FAILS on two of three lines. Bard's counts (33, 36) do not match Projects.md. Nothing retyped. Request sent to Bard to lock against Projects.md verbatim.

Crown skeptic page status:
- Body markup: returned with closing div.
- Style block: returned with closing style tag, selectors do not cover body classes. Rerun queued.
- Page not assembled. No proposal until the full document is verified.

Standing rule reinforced: a lock is a check against Projects.md, not a retype.