# Copy: Rewrite the watcher style block only under 40 lines ending

Date: 2026-11-01
Task: Rewrite the Watcher style block only, under 40 lines, ending with the closing style tag.
For [[Herald]].

<style>
:root{--accent:#ff2d8f;--ink:#f2f2f5;--muted:#9a9aa8;--panel:#12121a;--base:#0a0a10}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{background:var(--base);color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6;min-height:100vh;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background:radial-gradient(900px 600px at 15% -10%,rgba(255,45,143,.22),transparent 60%),radial-gradient(700px 500px at 90% 20%,rgba(255,45,143,.14),transparent 60%),radial-gradient(800px 600px at 50% 110%,rgba(255,45,143,.10),transparent 60%),linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:auto,auto,auto,56px 56px,56px 56px}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.6) 100%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
h1{font-size:clamp(2rem,5vw,3.4rem);line-height:1.1;margin:.6em 0 .3em;letter-spacing:-.01em}
h2{font-size:clamp(1.3rem,3vw,1.8rem);margin:1.6em 0 .5em}
h1 span,h2 span{color:var(--accent)}
p{max-width:68ch;margin:0 0 1em}
.muted{color:var(--muted)}
.eyebrow{color:var(--accent);text-transform:uppercase;letter-spacing:.14em;font-size:.78rem;font-weight:700}
.panel{background:var(--panel);border:1px solid rgba(255,255,255,.07);border-radius:14px;padding:clamp(18px,3vw,28px)}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:12px 0}
.chip{border:1px solid rgba(255,45,143,.45);color:var(--ink);padding:4px 12px;border-radius:999px;font-size:.85rem}
.tablewrap{width:100%;overflow-x:auto;border-radius:12px;border:1px solid rgba(255,255,255,.07);background:var(--panel);margin:16px 0}
table{width:100%;border-collapse:collapse;font-size:.95rem}
th,td{padding:10px 14px;text-align:left;border-bottom:1px solid rgba(255,255,255,.06)}
th{color:var(--muted);font-weight:600}
.figure{margin:20px 0}
.figure figcaption{color:var(--muted);font-size:.85rem;margin-top:8px}
a{color:var(--accent)}
</style>
