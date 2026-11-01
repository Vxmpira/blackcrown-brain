# Copy: Rewrite watcher style block as css only under 40 lines

Date: 2026-11-01
Task: Rewrite Watcher style block as CSS only, under 40 lines, ending with closing style tag.
For [[Herald]].

<style>
:root {
  --accent: #ff2d8f;
  --base: #0a0a10;
  --ink: #f2f2f5;
  --muted: #9a9aa8;
}
html, body {
  margin: 0;
  background: var(--base);
  color: var(--ink);
  -webkit-font-smoothing: antialiased;
}
body::before {
  content: "";
  position: fixed;
  inset: 0;
  z-index: -2;
  pointer-events: none;
  background:
    radial-gradient(60% 50% at 15% 0%, rgba(255, 45, 143, 0.16), transparent 70%),
    radial-gradient(50% 45% at 90% 100%, rgba(255, 45, 143, 0.10), transparent 70%);
}
body::after {
  content: "";
  position: fixed;
  inset: 0;
  z-index: -1;
  pointer-events: none;
  background:
    radial-gradient(ellipse at center, transparent 55%, rgba(0, 0, 0, 0.6) 100%),
    repeating-linear-gradient(0deg, rgba(255, 255, 255, 0.015) 0 1px, transparent 1px 56px),
    repeating-linear-gradient(90deg, rgba(255, 255, 255, 0.015) 0 1px, transparent 1px 56px);
}
.muted {
  color: var(--muted);
}
.accent {
  color: var(--accent);
}
</style>
