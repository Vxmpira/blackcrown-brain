# Copy: Check watcher style part one for brace balance length em

Date: 2026-10-30
Task: Check Watcher style part one for brace balance, length, em dashes, and style tags
For [[Herald]].

**Watcher style part one: check report**

| Check | Result | Detail |
|---|---|---|
| Brace balance | PASS | 3 open `{`, 3 close `}`. Blocks: `:root`, `html`, `body`. |
| Character count | Info | 554 characters excluding line breaks (558 with the 4 line breaks). |
| Line count | Info | 5 lines. |
| Em dashes | PASS | None found. |
| Style tags | FAIL | No `<style>` opening or `</style>` closing tag. The draft is bare CSS and cannot ship as-is. The wrapper must come from the host document. |
| Stray character | FAIL | A period follows the final `}` on line 5 (`fixed}.`). It sits outside any rule and needs to be removed before shipping. |

Text not rewritten, per instructions. Once the `<style>` wrapper is added and the stray period is removed, the brace and em dash checks still hold.
