# Copy: Rewrite the watcher style block under 40 lines ending with

Date: 2026-11-01
Task: Rewrite the Watcher style block under 40 lines, ending with </style>. Output raw CSS inside one style element only, no code fences, no script.
For [[Herald]].

<style>
:root{--accent:#ff2d8f;--ink:#f2f2f5;--muted:#9a9aa8;--panel:#12121a;--base:#0a0a10}
*{box-sizing:border-box}
html,body{margin:0;background:var(--base);color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6}
body{position:relative;isolation:isolate;min-height:100vh}
body::before{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;
background:
radial-gradient(60vmax 40vmax at 12% 8%,rgba(255,45,143,.14),transparent 70%),
radial-gradient(50vmax 36vmax at 88% 30%,rgba(255,45,143,.09),transparent 70%),
radial-gradient(70vmax 45vmax at 50% 110%,rgba(255,45,143,.10),transparent 70%),
linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px) 0 0/56px 56px,
linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px) 0 0/56px 56px,
radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.6) 100%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
h1,h2,h3{line-height:1.2;margin:0 0 .5em}
h1{font-size:clamp(1.9rem,5vw,3rem)}
h2{font-size:clamp(1.4rem,3.5vw,2rem)}
h3{font-size:clamp(1.1rem,2.6vw,1.35rem)}
p,li{max-width:75ch}
a{color:var(--accent)}
.muted{color:var(--muted)}
.panel{background:var(--panel);border:1px solid rgba(255,255,255,.07);border-radius:12px;padding:clamp(16px,3vw,24px)}
.grid{display:grid;gap:16px;grid-template-columns:repeat(3,1fr)}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
.tablewrap{width:100%;overflow-x:auto;border-radius:12px;border:1px solid rgba(255,255,255,.07)}
table{width:100%;border-collapse:collapse}
th,td{text-align:left;padding:10px 14px;border-bottom:1px solid rgba(255,255,255,.06)}
th{color:var(--muted);font-weight:600}
figure{margin:0;width:100%}
.chip{display:inline-block;padding:4px 10px;border-radius:999px;border:1px solid rgba(255,45,143,.4);color:var(--accent);font-size:.85rem}
.btn{display:inline-block;padding:12px 20px;border-radius:8px;background:var(--accent);color:var(--base);font-weight:700;text-decoration:none}
</style>
