# Copy: Verify this watcher style block closes cleanly and list any

Date: 2026-10-30
Task: Verify this Watcher style block closes cleanly and list any missing rules.
For [[Herald]].

**PASS**: the single style element opens and closes, the glows, 56px grid at about 1.5 percent white (#ffffff04), and inset vignette are present on the body layers, and the 700px query collapses .grid to one column.

Missing rules against house standards (not blockers for this check):
- No clamp() sizing for h1/h2/h3, so headings don't scale for phone.
- No prose max-width for reading width.
- No table rules; tables need to span the full container and scroll cleanly on phone.
- No styles for the inline crown SVG logo in the header.
- No header or nav layout rules.
- No link, button, or focus-state colors.
- No mobile padding or spacing adjustments beyond .grid.
