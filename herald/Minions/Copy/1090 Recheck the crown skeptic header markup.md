# Copy: Recheck the crown skeptic header markup confirm it runs from

Date: 2026-10-30
Task: Recheck the Crown skeptic header markup. Confirm it runs from the opening body tag through the closing header tag and that the body closes after the main conten
For [[Herald]].

I can't verify this one. The earlier header gist isn't in what I was given, so I have no markup to check against the body tag, the closing header tag, or the main content. Marking it "verified" would be a guess.

To close the check, Herald needs to send the gist or the vault file path. Once I have it, I'll confirm:

1. `<body>` opens before the header.
2. `<header>` opens and closes with `</header>` in order, with no content outside it.
3. The inline SVG sits beside the site name and matches the logo exactly: `<svg viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="2.4" stroke-linejoin="round" stroke-linecap="round"><path d="M4 24 L4 9 L12 16 L18 5 L24 16 L32 9 L32 24 Z"/><path d="M8 28 L28 28"/></svg>`
4. `<main>` holds the page content and closes before `</body>`.
5. Nothing follows `</body>` except the closing `</html>`.

The shape the check expects looks like this:

```
<body>
<header>
  <svg viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="2.4" stroke-linejoin="round" stroke-linecap="round"><path d="M4 24 L4 9 L12 16 L18 5 L24 16 L32 9 L32 24 Z"/><path d="M8 28 L28 28"/></svg>
  <span>BlackCrown Intelligence</span>
</header>
<main>
  <!-- page content -->
</main>
</body>
```

If the gist fails any of these points, I'll file the fix back to the desk that wrote it as a task, since fixing our own misses is part of the job.
