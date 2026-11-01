# Copy: Rewrite watcher style part a from the first line closing

Date: 2026-11-01
Task: Rewrite Watcher style part A from the first line, closing tag required
For [[Herald]].

<style>
*, *::before, *::after { box-sizing: border-box; }
html, body { margin: 0; padding: 0; }
html { background: #080810; color-scheme: dark; }
body {
  color: #e9e9f1;
  font-family: system-ui, sans-serif;
  font-size: 16px;
  line-height: 1.6;
  min-height: 100vh;
  overflow-x: hidden;
  position: relative;
}
body::before {
  content: "";
  position: fixed;
  inset: 0;
  pointer-events: none;
  z-index: -2;
  background:
    radial-gradient(circle at 12% 18%, rgba(255,45,143,0.16), transparent 38%),
    radial-gradient(circle at 88% 28%, rgba(120,80,255,0.18), transparent 40%),
    radial-gradient(circle at 50% 92%, rgba(255,45,143,0.10), transparent 42%),
    linear-gradient(rgba(255,255,255,0.015) 1px, transparent 1px),
    linear-gradient(90deg, rgba(255,255,255,0.015) 1px, transparent 1px);
  background-size: auto, auto, auto, 56px 56px, 56px 56px;
}
</style>
