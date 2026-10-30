# Copy: Rewrite the crown skeptic style block only opening style tag

Date: 2026-10-30
Task: Rewrite the Crown skeptic style block only: opening style tag through closing style tag, under 40 lines, no script, no code fences.
For [[Herald]].

<style>
  :root { --accent: #ff2d8f; --ink: #f2f2f5; --muted: #a7a9b4; --line: rgba(255,255,255,.08); }
  * { box-sizing: border-box; }
  html, body { margin: 0; }
  body {
    min-height: 100vh;
    color: var(--ink);
    font: 17px/1.6 system-ui, -apple-system, "Segoe UI", Roboto, sans-serif;
    background-color: #08080d;
    background-image:
      radial-gradient(640px 420px at 12% 8%, rgba(255,45,143,.16), transparent 70%),
      radial-gradient(560px 380px at 90% 32%, rgba(255,45,143,.10), transparent 70%),
      radial-gradient(720px 480px at 50% 110%, rgba(255,45,143,.09), transparent 70%),
      linear-gradient(rgba(255,255,255,.015) 1px, transparent 1px),
      linear-gradient(90deg, rgba(255,255,255,.015) 1px, transparent 1px);
    background-size: auto, auto, auto, 56px 56px, 56px 56px;
    background-attachment: fixed;
  }
  body::after {
    content: ""; position: fixed; inset: 0; pointer-events: none;
    background: radial-gradient(ellipse at center, transparent 55%, rgba(0,0,0,.55) 100%);
  }
  .wrap { max-width: 1060px; margin: 0 auto; padding: 0 20px; position: relative; z-index: 1; }
  header {
    display: flex; align-items: center; justify-content: space-between; gap: 16px;
    padding: 28px 0; border-bottom: 1px solid var(--line);
  }
  .hero { padding: 56px 0 40px; }
  .hero h1 { font-size: clamp(1.9rem, 4.6vw, 3.1rem); line-height: 1.12; letter-spacing: -.01em; margin: 0 0 16px; }
  .hero p { max-width: 75ch; color: var(--muted); margin: 0 0 14px; }
  .chips { list-style: none; padding: 0; margin: 22px 0 0; display: flex; flex-wrap: wrap; gap: 10px; }
  .chips li {
    border: 1px solid rgba(255,45,143,.45); background: rgba(255,45,143,.06);
    color: var(--ink); padding: 7px 14px; border-radius: 999px; font-size: .9rem;
  }
  .grid { display: grid; grid-template-columns: repeat(2, 1fr); gap: 18px; }
  @media (max-width: 700px) {
    .grid { grid-template-columns: 1fr; }
    header { flex-direction: column; align-items: flex-start; }
  }
</style>
