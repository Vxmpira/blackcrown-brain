# Copy: Verify the watcher draft report whether it ends with body

Date: 2026-10-30
Task: Verify the Watcher draft: report whether it ends with </body></html> and list any missing sections.
For [[Herald]].

**Watcher Draft Verification: BLOCKED, draft not readable**

**Status:** I could not read the Watcher draft. No file contents came through with this task, and I don't have vault access from this call. I have not inferred or reconstructed any part of the draft, so every check below is still open.

**What is unverified:**

1. **Last 200 characters:** not retrieved.
2. **`</body>` and `</html>` once each, after all content:** not checked.
3. **Sections (hero, features, footer):** not checked.
4. **Unclosed tags:** not checked.

**To finish this pass, one of the following is needed:**

- The full draft pasted into the task, or
- The exact vault path (for example, the FROM NOTE path), so a reader can pull the file.

**Checks to run once the draft is available:**

- Last 200 characters: take the final 200 characters verbatim, including whitespace.
- Closing tags: count occurrences of `</body>` and `</html>`. Each should appear exactly once, and both should come after every other element. Confirm nothing follows `</html>`.
- Sections: confirm a hero block, a features block (feature chips or a grid counts), and a footer element.
- Tag balance: check every opened element has a matching close, with attention to `<div>`, `<section>`, `<header>`, `<footer>`, `<main>`, and `<svg>`.
- House rules: confirm no em dashes, no emoji, an inline crown SVG in the header, and at least one real visual element (data mock, svg figure, or feature chips).

**Filing note:** this is a verification note, not a proposal, so nothing needs owner approval. Herald can reissue the task with the draft attached or the path given, and the pass will run against the real file.
