# Copy: Check combined watcher style block opening and closing style tags

Date: 2026-11-01
Task: Check combined Watcher style block: opening and closing style tags, under 40 lines, no inline script. Return PASS or the exact fix.
For [[Herald]].

**FAIL**

**Exact fix:** Add an opening `<style>` tag as the first line of the combined block, directly above the `:root{...}` rule from Part 1. The block then starts and ends with a matching pair:

```
<style>
:root{--accent:#ff2d8f; ...} body{...}
.container{...} h1{...} ...
.prose{max-width:75ch}
</style>
```

Everything else passes:
- **Closing tag:** `</style>` is present once, at the end.
- **Length:** about 11 lines, well under 40.
- **Inline script:** none.
