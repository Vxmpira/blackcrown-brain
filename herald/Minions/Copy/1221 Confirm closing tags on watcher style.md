# Copy: Confirm closing tags on watcher style parts one and two

Date: 2026-10-31
Task: Confirm closing tags on Watcher style parts one and two, return the joined style block only.
For [[Herald]].

I can't confirm this yet. Neither style part came through, only the description of them. I don't have the CSS for part one or part two, so I can't check for a closing `</style>`, count lines, or scan for a `<script>`, and I won't reconstruct the block from the description, since that could ship CSS that differs from what's live.

To finish the check, send the raw text of both parts, pasted in order. I'll then:

1. Verify part one ends at the body::before rule and part two closes with `</style>`.
2. Confirm the joined block opens with `<style>` and contains exactly one opening and one closing style tag.
3. Count lines and confirm the total is under 40.
4. Confirm there is no `<script>` or other script content.
5. Return the joined block only, with no fences and no commentary.

If the joined block fails any check, I'll say which one and where, so the fix goes back to the desk that filed the parts.
