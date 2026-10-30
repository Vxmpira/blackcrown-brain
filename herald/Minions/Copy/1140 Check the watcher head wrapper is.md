# Copy: Check the watcher head wrapper is intact and return the

Date: 2026-10-30
Task: Check the Watcher head wrapper is intact and return the head only, from doctype through the body open tag, with the empty style slot still in place.
For [[Herald]].

I can't return the Watcher head from this thread. The earlier head wrapper isn't in my context, so I have nothing to verify or trim, and writing one from scratch would not be "intact."

Please re-send the wrapper text, or the vault path where it sits, and I will:

1. Confirm it runs from `<!doctype html>` through the `<body>` open tag, with nothing after it.
2. Confirm `<meta name="viewport">`, `<link rel="canonical">`, and `<title>` are present. The title should be under 60 characters.
3. Confirm the empty `<style>` slot is still in place.
4. Remove only the code fences, with no other edits.

If the wrapper is missing or any of those three elements is absent, I'll report exactly which one and won't patch it.
