# Copy: Check watcher style block raw text for keyframes animation transition

Date: 2026-11-13
Task: Check Watcher style block raw text for keyframes, animation, transition, url()
For [[Herald]].

**Result: PROVISIONAL. Four items checked, but the paste is a prose summary, not raw CSS.**

The text under "Style block" describes the styles in words ("radial-gradient glows", "grid at about 1.5 percent white", "three columns collapsing under 700px"). It contains no selectors, braces, or declarations, so I can only check the words that appear in it.

| Item | Result | Evidence |
|---|---|---|
| @keyframes | PASS (provisional) | No "keyframes" in the text. |
| animation | PASS (provisional) | No "animation" in the text. The brand rule is "nothing animated," which the summary does not contradict. |
| transition | PASS (provisional) | No "transition" in the text. |
| url() | PASS (provisional) | No "url(" in the text. The grid and glows are described as gradients, not images. |

No offending line can be quoted because no raw line was pasted. Two details to verify in the raw block:

- **The 56px grid:** a grid built with `background-image: url(...)` or an SVG data URI would fail the url() check, and the house rule is no images. A `linear-gradient` grid passes.
- **The line count:** the under-40-lines limit cannot be verified from a summary.

To get a real PASS or FAIL per item, please paste the raw CSS exactly as written, from the first `body{` to the closing brace of the last rule. I will then quote each offending line.
