# Auditor: Diagnose why the observer comparison page duplicates the head tag

Date: 2026-10-27
Task: Diagnose why the observer comparison page duplicates the head tag
For [[Steward]].

**Diagnosis: not completed. I could not read the source.**

I have no repo or live-page access in this session, so I can't name the exact line or template. Any line number I gave you would be invented, and the owner's filing gates exist to prevent that kind of guess.

**What the guard codes point to:** 107, 109, 111, and 113 all fired on a duplicate head tag. Each one blocked the write before it reached the live site, so production is unaffected. Four failures on the same check mean the builder reproduces the defect every time. It is not intermittent.

**Candidates to check, ranked by fit with the box layout in memory:**

1. **Full document wrapped around an existing head.** The write path takes a complete document and inserts it into a shell that already has `<head>`, or it prepends a head block to a body that already has one. This is the most likely cause.
2. **Bar fragment carrying head content.** `blackcrown-bar.html` is body-only and robots-blocked. If the builder pulls it in and that fragment, or a copy of it, contains a `<head>` or meta tags, the result gets two heads. Memory says the fragment can never take meta tags, so a head in it would be a builder bug.
3. **Template injecting a head that the source document already contains.** The author's complete document gets a second head from the template layer. This would show up as the head tag appearing twice in the template output, not only in the final file.

**Evidence needed to confirm one of these:**
- The builder or template file that writes the observer comparison page, and the exact lines that emit `<head>`.
- The output of that build for one run, with the count of `<head` occurrences.
- The live page source, to confirm whether the duplicate was ever published or only exists in the staged build.

Once a desk reads those three items, the diagnosis and one-line fix can be written. Filing the fix back through Steward is the next move, and I'd suggest the desk that filed the four asks owns this, since the misses are its own.
