# Watcher Part One: Root Vars and Backdrop

Status: done. Feeds Watcher body part two (panel and chips) and the final assembly.

WHAT: root tokens, fixed backdrop layers, container and heading scale.

```css
:root {
  --bg: #07070c;
  --ink: #e9e7f2;
  --muted: #9a97ab;
  --accent: #ff2d8f;
  --accent-2: #6a5cff;
  --line: rgba(255, 255, 255, 0.08);
  --panel: rgba(16, 16, 26, 0.72);
  --max: 1060px;
  --radius: 14px;
}

html, body {
  margin: 0;
  background: var(--bg);
  color: var(--ink);
  font-family: system-ui, -apple-system, 'Segoe UI', sans-serif;
  line-height: 1.6;
  -webkit-font-smoothing: antialiased;
}

.backdrop {
  position: fixed;
  inset: 0;
  z-index: -1;
  pointer-events: none;
  background:
    radial-gradient(900px 620px at 12% 8%, rgba(255, 45, 143, 0.16), transparent 60%),
    radial-gradient(820px 580px at 88% 18%, rgba(106, 92, 255, 0.14), transparent 62%),
    radial-gradient(760px 520px at 50% 105%, rgba(255, 45, 143, 0.08), transparent 66%),
    var(--bg);
}

.backdrop::before {
  content: '';
  position: absolute;
  inset: 0;
  background-image:
    linear-gradient(rgba(255, 255, 255, 0.015) 1px, transparent 1px),
    linear-gradient(90deg, rgba(255, 255, 255, 0.015) 1px, transparent 1px);
  background-size: 56px 56px;
}

.backdrop::after {
  content: '';
  position: absolute;
  inset: 0;
  background: radial-gradient(ellipse at center, transparent 55%, rgba(0, 0, 0, 0.6) 100%);
}

.wrap {
  position: relative;
  z-index: 1;
  max-width: var(--max);
  margin: 0 auto;
  padding: 0 clamp(16px, 4vw, 32px);
}

.prose {
  max-width: 70ch;
}

h1 {
  font-size: clamp(2rem, 5vw, 3.6rem);
  line-height: 1.1;
  margin: 0.4em 0 0.3em;
}

h2 {
  font-size: clamp(1.4rem, 3vw, 2rem);
  line-height: 1.2;
}
```

CHECKS: tokens only, no images, no animation, no em dashes, no emoji. The grid sits at 1.5 percent white per standard. Container is about 1060px with side padding; prose caps at 70ch. Grids collapse under 700px in part two.

NEXT: part two builds the data panel and feature chips using these tokens and the inline crown SVG in the header.