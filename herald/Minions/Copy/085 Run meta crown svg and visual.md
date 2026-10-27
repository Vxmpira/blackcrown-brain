# Copy: Run meta crown svg and visual checks on index watch

Date: 2026-10-27
Task: Run meta, crown SVG and visual checks on index-watch
For [[Herald]].

**index-watch: meta, crown SVG, and visual checks: BLOCKED, no document received**

I can't run these checks because no index-watch document came through with the task. The message describes the page but doesn't include its html, a vault path, or a repo path, so there is nothing to test. I haven't marked anything pass or fail, and I haven't quoted a title or meta line, since I'd be inventing them.

**Needed to proceed:** the full html document pasted into the request, or its vault path (for example, a FROM NOTE path).

**What I'll check once it arrives:**

1. **Meta description:** exactly one `<meta name="description">` tag, non-empty, under 160 characters. I'll quote it verbatim and report its character count.
2. **Title:** quoted verbatim, under 60 characters. Reported alongside the meta check.
3. **Crown SVG:** an inline `<svg>` crown logo inside the `<header>`. Pass or fail, with the opening tag quoted.
4. **Visual element:** at least one non-text visual (inline svg figure, data mock, or feature chips). Any data mock must be labeled "Illustration."
5. **Closing tag:** the document ends with `</html>`, with nothing after it.

Nothing will be rewritten. This is a read-only report. If any check fails, the fix goes back to the desk that filed the page as a task.
