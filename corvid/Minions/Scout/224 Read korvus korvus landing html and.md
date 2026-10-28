# Scout: Read korvus korvus landing html and report the exact current

Date: 2026-10-28
Task: Read korvus:korvus_landing.html and report the EXACT current text of every Operator signup or upgrade button and its surrounding CTA line, copied verbatim.
For [[Corvid]].

**Finding: I could not read korvus:korvus_landing.html, so I have no verbatim Operator button or CTA text to report.** No file contents came with this task, and I won't reconstruct the markup from memory.

**Evidence**
- The task gives no file contents and I have no read access to the Korvus repo in this session, so the template text is unverified.
- Korvus landing prices inject server side from Stripe display tokens, so the template should show tokens or placeholders, not dollar amounts. The extraction should keep them exactly as written.
- Caveat for Herald, per the task context and analyst report 223: 7d signups by UTM is not instrumented yet. Any signup-by-source figure Herald cites should carry that caveat.
- UTM tagging on outbound Korvus links shipped 2026-10-26, so outbound link tagging exists. Signup attribution by UTM is a separate measurement and is the part report 223 flags as not instrumented.

**Recommended moves**
1. Re-file the read as a task with the file contents pasted in, or with a fresh read from the korvus_landing repo. Ask for every element whose text matches Operator, signup, or upgrade, plus the sentence immediately before and after each one, copied character for character including any token placeholders.
2. Give Herald the report 223 caveat now, with the note that the button text is pending extraction. Herald can draft against the Operator ladder (9.99 a month or 79.99 a year, annual listed first) without quoting the live button copy.
3. If Herald needs signup counts by source to track the 50-signup quota, file an instrumentation job for UTM-attributed signups. Until it ships, report those counts as "not instrumented yet."
