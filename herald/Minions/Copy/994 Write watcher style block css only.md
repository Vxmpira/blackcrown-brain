# Copy: Write watcher style block css only under 40 lines no

Date: 2026-10-30
Task: Write Watcher style block: CSS only, under 40 lines, no script, end with closing style tag.
For [[Herald]].

<style>
:root{--bg:#07070c;--pink:#ff2d8f;--cool:#2dd4ff;--ink:#e9e9f2;--mute:#9a9ab0}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{background-color:var(--bg);color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",sans-serif;line-height:1.6;min-height:100vh;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background:radial-gradient(60vmax 40vmax at 15% 0%,rgba(255,45,143,.22),transparent 70%),radial-gradient(50vmax 35vmax at 90% 10%,rgba(45,212,255,.16),transparent 70%),radial-gradient(45vmax 40vmax at 50% 100%,rgba(255,45,143,.10),transparent 70%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.65) 100%),linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:auto,56px 56px,56px 56px}
header{max-width:1060px;margin:0 auto;padding:24px clamp(16px,4vw,32px);display:flex;align-items:center;gap:14px}
header svg{width:40px;height:40px;flex:none}
.brand{font-weight:700;letter-spacing:.14em;text-transform:uppercase;font-size:.85rem}
section.hero{max-width:1060px;margin:0 auto;padding:clamp(32px,8vw,96px) clamp(16px,4vw,32px);display:grid;grid-template-columns:1.1fr .9fr;gap:40px;align-items:center}
.hero h1{font-size:clamp(2rem,5.5vw,3.6rem);line-height:1.08;letter-spacing:-.02em;margin:0 0 20px;font-weight:800}
.hero p{max-width:75ch;color:var(--mute);margin:0 0 24px}
.chips{display:flex;flex-wrap:wrap;gap:8px}
.chips span,span.chips{display:inline-block;padding:6px 12px;border:1px solid rgba(255,45,143,.45);border-radius:999px;font-size:.8rem;color:var(--ink);background:rgba(45,212,255,.06)}
@media (max-width:699px){
header{flex-direction:column;align-items:flex-start;gap:12px}
section.hero{grid-template-columns:1fr;gap:24px}
}
</style>
