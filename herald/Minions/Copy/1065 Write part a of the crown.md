# Copy: Write part a of the crown skeptic page style block

Date: 2026-10-30
Task: Write part A of the Crown skeptic page style block: opening <style> tag, :root color variables, box-sizing reset, html and body base, and the fixed body::before
For [[Herald]].

<style>
:root {
  --bg: #07070c;
  --ink: #e9e7f2;
  --muted: #9a97ab;
  --accent: #ff2d8f;
  --accent-soft: rgba(255, 45, 143, 0.18);
  --accent-faint: rgba(255, 45, 143, 0.08);
  --line: rgba(255, 255, 255, 0.08);
  --max: 1060px;
  --read: 68ch;
}

*,
*::before,
*::after {
  box-sizing: border-box;
}

html {
  -webkit-text-size-adjust: 100%;
  text-size-adjust: 100%;
  scroll-behavior: auto;
}

body {
  margin: 0;
  min-height: 100vh;
  background-color: var(--bg);
  color: var(--ink);
  font-family: system-ui, -apple-system, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  font-size: 1rem;
  line-height: 1.6;
  -webkit-font-smoothing: antialiased;
  position: relative;
  isolation: isolate;
}

body::before {
  content: "";
  position: fixed;
  inset: 0;
  z-index: -1;
  pointer-events: none;
  background-color: var(--bg);
  background-image:
    radial-gradient(900px 600px at 12% -10%, var(--accent-soft), transparent 60%),
    radial-gradient(800px 560px at 92% 8%, var(--accent-faint), transparent 62%),
    radial-gradient(700px 500px at 50% 110%, var(--accent-faint), transparent 65%),
    linear-gradient(to right, rgba(255, 255, 255, 0.015) 1px, transparent 1px),
    linear-gradient(to bottom, rgba(255, 255, 255, 0.015) 1px, transparent 1px),
    radial-gradient(ellipse at center, transparent 55%, rgba(0, 0, 0, 0.55) 100%);
  background-size:
    auto,
    auto,
    auto,
    56px 56px,
    56px 56px,
    auto;
  background-position:
    0 0,
    0 0,
    0 0,
    0 0,
    0 0,
    0 0;
}
</style>
