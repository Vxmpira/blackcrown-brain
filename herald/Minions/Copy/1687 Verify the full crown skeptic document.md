# Copy: Verify the full crown skeptic document ends with main body

Date: 2026-11-13
Task: Verify the full Crown skeptic document ends with </main></body></html> after Part 1 returns
For [[Herald]].

**Result: NOT VERIFIED.** I can't run this check because neither Part 1 nor Part 2 is in my context. No assembled text was included, so I have nothing to check the closing sequence against.

To complete the check, I need one of the following:

1. **The assembled document**, or at least its last few hundred characters plus the position of the `<main>` opening tag.
2. **Part 1 and Part 2 separately**, so I can concatenate them and check.

Two things to settle before the check runs:

- **Marker conflict.** The brief says Part 2 "ends with `</main>` then END PART 2," but also that the closing tags are `</body></html>`. If the literal text `END PART 2` appears in the assembled output, the document will not end with `</main></body></html>`. The marker needs to be stripped before assembly, or the check should exempt it.
- **Pairing rule.** PASS requires that the opening `<main>` in the assembled text pairs with the closing `</main>`. If Part 1 opens `<main>` and Part 2 closes it, that pairing holds, but only if there is exactly one `<main>` and one `</main>` in the combined text.

If you paste the assembled output, I'll report PASS or the exact mismatch.
