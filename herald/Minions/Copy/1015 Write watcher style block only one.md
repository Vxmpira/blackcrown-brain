# Copy: Write watcher style block only one style element under 40

Date: 2026-10-30
Task: Write Watcher style block only, one style element, under 40 lines, no script.
For [[Herald]].

<style>
  :root { --accent: #ff2d8f; --violet: #8b5cf6; --ink: #ece9f4; --muted: #9a94ab; --line: rgba(255,255,255,.08); }
  * { box-sizing: border-box; }
  html, body { margin: 0; }
  body { background: #07060b; color: var(--ink); font: 16px/1.6 system-ui, -apple-system, "Segoe UI", sans-serif; min-height: 100vh; }
  body::before { content: ""; position: fixed; inset: 0; z-index: -2; pointer-events: none;
    background:
      radial-gradient(900px 600px at 15% 10%, rgba(255,45,143,.18), transparent 60%),
      radial-gradient(800px 560px at 88% 30%, rgba(139,92,246,.16), transparent 60%),
      radial-gradient(700px 500px at 50% 100%, rgba(255,45,143,.10), transparent 65%),
      linear-gradient(rgba(255,255,255,.015) 1px, transparent 1px),
      linear-gradient(90deg, rgba(255,255,255,.015) 1px, transparent 1px);
    background-size: auto, auto, auto, 56px 56px, 56px 56px; }
  body::after { content: ""; position: fixed; inset: 0; z-index: -1; pointer-events: none;
    background: radial-gradient(ellipse at center, transparent 55%, rgba(0,0,0,.75) 100%); }
  .wrap, header, main, footer { width: min(1060px, 100% - 40px); margin-inline: auto; }
  header { display: flex; align-items: center; justify-content: space-between; gap: 16px; padding: 22px 0; border-bottom: 1px solid var(--line); }
  main { padding: clamp(32px, 6vw, 72px) 0; }
  .hero { display: grid; gap: 28px; grid-template-columns: 1.15fr .85fr; align-items: center; }
  .headline { font-size: clamp(2rem, 5.2vw, 3.6rem); line-height: 1.08; letter-spacing: -.02em; margin: 0 0 16px; font-weight: 800; }
  .headline span { color: var(--accent); }
  .hero p { max-width: 62ch; color: var(--muted); margin: 0 0 20px; }
  .chips { display: flex; flex-wrap: wrap; gap: 8px; margin: 0; padding: 0; list-style: none; }
  .tag { display: inline-block; padding: 5px 12px; border-radius: 999px; font-size: .8rem; border: 1px solid rgba(255,45,143,.45); color: var(--ink); background: rgba(255,45,143,.08); }
  .panel { background: rgba(14,12,22,.72); border: 1px solid var(--line); border-radius: 14px; padding: 22px; backdrop-filter: blur(6px); }
  .panel h3 { margin: 0 0 8px; font-size: 1.05rem; }
  .panel p { margin: 0; color: var(--muted); font-size: .95rem; }
  footer { padding: 24px 0 36px; border-top: 1px solid var(--line); color: var(--muted); font-size: .85rem; }
  @media (max-width: 700px) { .hero { grid-template-columns: 1fr; } header { flex-direction: column; align-items: flex-start; } }
</style>
