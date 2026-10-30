# Copy: Check watcher style rewrite for brace balance length em dashes

Date: 2026-10-30
Task: Check Watcher style rewrite for brace balance, length, em dashes, stray characters, and closing rule
For [[Herald]].

**Watcher style CSS check**

1. **Brace balance: PASS.** Four opening braces and four closing braces, one pair per rule: `:root`, `html,body`, `body`, and the closing brace of `body` on line 3.
2. **Parenthesis and quote balance: PASS.** Both `radial-gradient(...)` calls close correctly around their nested `rgba(...)`. The `"Segoe UI"` quotes are paired.
3. **Length: PASS.** About 550 characters, three rules. No length limit was given for this check, so this is a compactness note only.
4. **Em dashes: PASS.** None found.
5. **Stray characters: FAIL.** A period follows the final closing brace of the `body` rule (`...line-height:1.6}.`). It is the only stray character in the draft.
6. **Closing rule: FAIL.** The final character is a period, not the closing brace of the `body` rule. The brace is the second-to-last character. The required ending is the brace with no trailing period.

**Fix:** Delete the single trailing period so the draft ends on `}`. The text is otherwise unchanged. The desk that filed this draft should make that correction and resubmit it.
