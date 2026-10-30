# Copy: Write the watcher hero style block as css only under

Date: 2026-10-30
Task: Write the Watcher hero style block as CSS only, under 40 lines, closing style tag.
For [[Herald]].

<style>
:root{--accent:#ff2d8f;--bg:#07060b;--ink:#ece9f2;--mute:#9a95a8}
*{box-sizing:border-box}
body{margin:0;min-height:100vh;color:var(--ink);background-color:var(--bg);
background-image:
radial-gradient(900px 520px at 12% -8%,rgba(255,45,143,.16),transparent 60%),
radial-gradient(720px 480px at 92% 8%,rgba(255,45,143,.09),transparent 62%),
radial-gradient(640px 420px at 50% 115%,rgba(120,60,255,.09),transparent 60%),
linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),
linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);
background-size:auto,auto,auto,56px 56px,56px 56px;
background-attachment:fixed}
body::after{content:"";position:fixed;inset:0;pointer-events:none;z-index:0;
background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.6) 100%)}
.hero{position:relative;z-index:1}
.watch-hero{max-width:1060px;margin:0 auto;padding:72px 20px 56px;display:grid;grid-template-columns:1.1fr .9fr;gap:40px;align-items:center}
.hero h1{font-size:clamp(2rem,5vw,3.4rem);line-height:1.08;letter-spacing:-.01em;margin:0 0 16px}
.hero p{max-width:75ch;color:var(--mute);font-size:clamp(1rem,1.6vw,1.1rem);line-height:1.6;margin:0 0 18px}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:20px 0}
.chips span{border:1px solid rgba(255,45,143,.45);background:rgba(255,45,143,.06);color:var(--ink);padding:6px 12px;border-radius:999px;font-size:.85rem}
.illus{border:1px solid rgba(255,255,255,.08);border-radius:14px;background:rgba(10,8,16,.7);padding:18px;box-shadow:0 0 40px rgba(255,45,143,.12)}
.illus svg{display:block;width:100%;height:auto}
.cta{display:inline-block;background:var(--accent);color:#0a0610;font-weight:700;text-decoration:none;padding:12px 22px;border-radius:8px;margin-top:8px}
.fine{color:var(--mute);font-size:.8rem;line-height:1.5;max-width:75ch;margin-top:14px}
@media (max-width:699px){.watch-hero{grid-template-columns:1fr;padding:48px 16px 40px;gap:28px}}
</style>
