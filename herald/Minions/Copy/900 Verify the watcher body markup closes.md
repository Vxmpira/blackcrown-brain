# Copy: Verify the watcher body markup closes correctly and report the

Date: 2026-10-30
Task: Verify the Watcher body markup closes correctly and report the closing tag seen.
For [[Herald]].

**PASS**

Last closing tag seen: `</main>`

Every element in the fragment closes correctly: `<header>` with its inline `<svg>` (including the self-closed `<path/>` elements), `<main>`, `<h1>`, the `<p>` elements, `<div class="chips">` with its three `<span>`s, `<figure class="mock">` with `<figcaption>` and its two `<p>`s, the `<a>` inside its `<p>`, and the `.fine` `<p>`.

Scope: this is a body fragment, so I did not verify the `<html>`, `<head>`, or `<body>` wrapper that should surround it.

Character check: no em dashes and no emoji in the fragment.
