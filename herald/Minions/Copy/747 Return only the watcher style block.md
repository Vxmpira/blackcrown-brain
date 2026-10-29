# Copy: Return only the watcher style block under 40 lines no

Date: 2026-10-29
Task: Return only the Watcher style block, under 40 lines, no script, last line </style>.
For [[Herald]].

<style>
:root{--accent:#ff2d8f;--accent2:#3aa0ff;--text:#e9ecf4;--muted:#9aa3b8;--bg:#07080d}
*{box-sizing:border-box;margin:0;padding:0}
html,body{background:var(--bg);color:var(--text);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6}
body{min-height:100vh;position:relative;overflow-x:hidden;
background:
radial-gradient(900px 600px at 15% -10%,rgba(255,45,143,.18),transparent 60%),
radial-gradient(800px 560px at 90% 10%,rgba(58,160,255,.16),transparent 60%),
radial-gradient(700px 500px at 50% 110%,rgba(255,45,143,.10),transparent 60%),
var(--bg)}
body::before{content:"";position:fixed;inset:0;pointer-events:none;z-index:-2;
background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);
background-size:56px 56px}
body::after{content:"";position:fixed;inset:0;pointer-events:none;z-index:-1;
background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.65) 100%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
h1,h2{font-size:clamp(1.6rem,4vw,2.6rem);line-height:1.15;color:var(--text)}
p{color:var(--muted);max-width:68ch}
.accent{color:var(--accent)}
.accent2{color:var(--accent2)}
.chips{display:flex;flex-wrap:wrap;gap:8px}
.chip{border:1px solid rgba(255,255,255,.12);border-radius:999px;padding:4px 12px;font-size:.85rem;color:var(--text);background:rgba(255,255,255,.03)}
.figure{border:1px solid rgba(255,255,255,.1);border-radius:14px;background:rgba(10,12,20,.7);padding:20px;width:100%}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
.btn{display:inline-block;background:var(--accent);color:#07080d;padding:10px 18px;border-radius:10px;text-decoration:none;font-weight:600}
.btn.alt{background:transparent;color:var(--accent2);border:1px solid var(--accent2)}
table{width:100%;border-collapse:collapse}
td,th{padding:10px;border-bottom:1px solid rgba(255,255,255,.08);text-align:left}
</style>
