# Copy: Rewrite watcher style block 30 to 40 lines closing style

Date: 2026-11-01
Task: Rewrite Watcher style block, 30 to 40 lines, closing style tag required
For [[Herald]].

<style>
:root {
  --accent: #ff2d8f;
  --ink: #f2f2f6;
  --muted: #a7a9b8;
  --glass: rgba(20, 20, 28, 0.62);
  --line: rgba(255, 255, 255, 0.09);
}
*, *::before, *::after { box-sizing: border-box; }
body {
  margin: 0;
  color: var(--ink);
  font-family: system-ui, -apple-system, "Segoe UI", Roboto, sans-serif;
  background:
    radial-gradient(60% 40% at 15% 0%, rgba(255, 45, 143, 0.18), transparent 70%),
    radial-gradient(50% 35% at 90% 10%, rgba(120, 90, 255, 0.12), transparent 70%),
    linear-gradient(rgba(255, 255, 255, 0.035) 1px, transparent 1px) 0 0 / 44px 44px,
    linear-gradient(90deg, rgba(255, 255, 255, 0.035) 1px, transparent 1px) 0 0 / 44px 44px,
    #0b0b12;
  min-height: 100vh;
}
body::after { content: ""; position: fixed; inset: 0; pointer-events: none; background: radial-gradient(120% 90% at 50% 50%, transparent 55%, rgba(0, 0, 0, 0.6) 100%); }
.wrap { max-width: 1060px; margin: 0 auto; padding: 0 clamp(16px, 4vw, 32px); }
.panel { background: var(--glass); border: 1px solid var(--line); border-radius: 16px; padding: clamp(20px, 3vw, 36px); backdrop-filter: blur(10px); box-shadow: 0 0 40px rgba(255, 45, 143, 0.08); }
.tag { display: inline-block; font-size: 12px; letter-spacing: .14em; text-transform: uppercase; color: var(--accent); border: 1px solid rgba(255, 45, 143, 0.4); border-radius: 999px; padding: 6px 12px; }
h1 { font-size: clamp(28px, 5vw, 52px); line-height: 1.1; margin: 14px 0; }
.chip-row { display: grid; grid-template-columns: repeat(4, 1fr); gap: 12px; margin-top: 24px; }
.chip { background: rgba(255, 255, 255, 0.03); border: 1px solid var(--line); border-radius: 12px; padding: 14px; color: var(--muted); }
.chip-title { color: var(--accent); font-weight: 700; margin: 0 0 6px; }
.chips { display: flex; flex-wrap: wrap; gap: 8px; }
.watcher-cta { display: inline-block; margin-top: 22px; background: var(--accent); color: #0b0b12; font-weight: 700; text-decoration: none; padding: 12px 22px; border-radius: 10px; box-shadow: 0 8px 30px rgba(255, 45, 143, 0.3); }
.watcher-cta:hover { filter: brightness(1.08); }
@media (max-width: 700px) {
  .chip-row { grid-template-columns: 1fr; }
}
</style>
