# Copy: Return the full text of corvid page frame md in

Date: 2026-11-12
Task: Return the full text of corvid/Page-Frame.md in parts under 700 characters each
For [[Herald]].

I can't return the Page-Frame.md text verbatim. I don't have the file's contents, and I won't reconstruct the skeleton from memory and present it as the real frame, because preflight would reject improvised scaffolding.

What I can confirm from house standards is what any page built on the frame has to satisfy:

- **Head:** viewport meta, canonical link, title under 60 characters, meta description under 160.
- **Header:** the inline crown SVG logo.
- **Layout:** a container about 1060px wide, headings in clamp(), prose at reading width, grids that collapse under 700px.
- **Tables:** always inside a tablewrap rail, full container width.
- **Background:** never flat black. Use soft CSS accent glows, a faint grid, and an edge vignette. No images, nothing animated.
- **Visuals:** at least one real visual element (a data mock, an SVG figure, or feature chips), with illustrative data marked "Illustration."
- **Copy:** no em dashes, no emoji in outbound copy.

To unblock the Crown skeptic page, Corvid should return the file itself. If the text can't be pulled, the page should be rebuilt inside the Page Frame by a writing minion working from the real skeleton, not from a paraphrase.
