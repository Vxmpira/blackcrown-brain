# Copy: Write one complete watcher style block from scratch

Date: 2026-10-31
Task: Write one complete Watcher style block from scratch
For [[Herald]].

<style>
:root {
  --bg: #07070b;
  --ink: #eceaf2;
  --muted: #9a97a8;
  --pink: #ff2d8f;
  --gold: #e8c35a;
}
body {
  margin: 0;
  position: relative;
  min-height: 100vh;
  background: var(--bg);
  color: var(--ink);
  font-family: system-ui, sans-serif;
  font-size: 16px;
  line-height: 1.6;
  overflow-x: hidden;
}
body::before {
  content: "";
  position: fixed;
  inset: 0;
  z-index: -2;
  pointer-events: none;
  background:
    radial-gradient(circle at 12% 8%, rgba(255, 45, 143, 0.18), transparent 40%),
    radial-gradient(circle at 88% 35%, rgba(232, 195, 90, 0.14), transparent 42%),
    radial-gradient(circle at 40% 100%, rgba(255, 45, 143, 0.14), transparent 45%);
}
body::after {
  content: "";
  position: fixed;
  inset: 0;
  z-index: -2;
  pointer-events: none;
  background:
    radial-gradient(ellipse at center, transparent 55%, rgba(0, 0, 0, 0.6) 100%),
    linear-gradient(rgba(255, 255, 255, 0.015) 1px, transparent 1px),
    linear-gradient(90deg, rgba(255, 255, 255, 0.015) 1px, transparent 1px);
  background-size: auto, 56px 56px, 56px 56px;
}
</style>
