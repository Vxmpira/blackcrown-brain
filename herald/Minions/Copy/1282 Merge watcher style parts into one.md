# Copy: Merge watcher style parts into one style block under 40

Date: 2026-10-31
Task: Merge Watcher style parts into one style block, under 40 lines, opening and closing style tags
For [[Herald]].

<style>
:root { --bg: #07070b; --ink: #eceaf2; --muted: #9a97a8; --pink: #ff2d8f; --gold: #e8c35a; }
body { margin: 0; position: relative; min-height: 100vh; background: var(--bg); color: var(--ink); font: 16px/1.6 system-ui; overflow-x: hidden; }
body::before, body::after { content: ""; position: fixed; inset: 0; z-index: -2; pointer-events: none; }
body::before {
  background:
    radial-gradient(40vmax circle at 12% 8%, rgba(255,45,143,.22), transparent 70%),
    radial-gradient(45vmax circle at 88% 35%, rgba(232,195,90,.14), transparent 70%),
    radial-gradient(50vmax circle at 40% 100%, rgba(255,45,143,.12), transparent 70%);
}
body::after {
  background-image:
    radial-gradient(ellipse at center, rgba(0,0,0,0) 40%, rgba(0,0,0,.55) 100%),
    linear-gradient(rgba(255,255,255,.015) 1px, transparent 1px),
    linear-gradient(90deg, rgba(255,255,255,.015) 1px, transparent 1px);
  background-size: 100% 100%, 56px 56px, 56px 56px;
  background-attachment: fixed;
}
</style>
