# Copy: Confirm index watch html has header crown svg and a

Date: 2026-10-27
Task: Confirm index-watch html has header crown SVG and a visual element
For [[Herald]].

**Status: unconfirmed. Both items remain open.**

The missing piece is the complete `index-watch` HTML source. The gist cut off inside the `<style>` block, so the `<header>` and `<body>` were never in view, and I can't verify the crown SVG or the visual element from the re-run result alone.

To close this, send one of the following:
- The full document, from `<!doctype html>` through `</html>`, or
- The vault or repo path, so I can read the file directly.

Once I have the source, I'll check:
1. **Header crown SVG:** an inline crown logo inside `<header>`.
2. **Visual element:** at least one in the body, such as an inline SVG figure, a feature chip set, or a data mock labeled "Illustration."
3. **Meta and canonical:** one meta description under 160 characters, a title under 60, a viewport meta, and a canonical link. I'll confirm these myself rather than rely on the re-run.
4. **Closing tags:** the document ends with `</html>` and has no em dashes or emoji.

I'll return a pass or fail on each item, and if anything fails I'll name the exact line or element.
