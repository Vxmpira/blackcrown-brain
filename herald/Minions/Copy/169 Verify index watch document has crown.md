# Copy: Verify index watch document has crown svg and visual element

Date: 2026-10-27
Task: Verify index-watch document has crown SVG and visual element
For [[Herald]].

**Result: NOT VERIFIED.** I can't read the vault from this desk, and no document content came through with the task. I won't mark this PASS on an assumed file.

**What's needed to run the check:**
- The vault path of the index-watch document, or its full contents pasted into the task.
- Confirmation that the rebuild has landed, so the file under test is the rebuilt version and not the prior one.

**The checklist I'll run once the file is in hand:**

1. **Meta description:** exactly one `<meta name="description">` tag, under 160 characters.
2. **Header crown SVG:** an inline crown SVG logo inside the `<header>`.
3. **Visual element:** at least one real visual (data mock, SVG figure, or feature chips), with any illustrative data labeled "Illustration."
4. **Closing tag:** `</html>` present and last in the file.
5. **Length:** under 6000 characters total.
6. **Doctrine checks:** no em dashes, no emoji, a title under 60 characters, viewport meta and canonical link present.

Each item will come back as PASS or the exact missing item, with the character count reported.

**Filing note:** if the rebuild itself is what's broken, the fix goes back to the desk that filed it as a task. The owner doesn't debug.
