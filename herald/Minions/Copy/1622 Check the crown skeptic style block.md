# Copy: Check the crown skeptic style block confirm it is closed

Date: 2026-11-13
Task: Check the Crown skeptic style block: confirm it is closed, under 450 characters, and carries no notes or trailing text.
For [[Herald]].

**Result: PASS on all three checks.**

- **Closed:** The block ends with `</style>` and every rule is terminated, including the `@media` group.
- **Under 450 characters:** Counted including the `<style>` and `</style>` tags, it is about 439 characters. That is close to the limit, so any added rule could push it over.
- **No notes or trailing text:** Nothing follows `</style>`.

**Page Frame background check: PASS.** The `body` background layers a purple radial glow (`#7850ff26`), a dark edge vignette (`radial-gradient(#0000 55%,#000a)`), a faint 56px grid (`#ffffff04` lines), and a `#0b0b12` base. It is not flat black.
