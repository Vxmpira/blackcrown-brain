# Copy: Rewrite the watcher page style block only under 35 lines

Date: 2026-10-31
Task: Rewrite the Watcher page style block only, under 35 lines, ending with the literal line </style>.
For [[Herald]].

<style>
:root{--bg:#07070b;--pink:#ff2d8f;--ink:#eef0f6;--mute:#9aa0b4;--line:rgba(255,255,255,.08)}
*{box-sizing:border-box}
html,body{margin:0;background:var(--bg);color:var(--ink);font-family:system-ui,-apple-system,Segoe UI,Roboto,sans-serif;line-height:1.6}
body{min-height:100vh;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;background-image:linear-gradient(rgba(255,255,255,.035) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.035) 1px,transparent 1px);background-size:44px 44px}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background:radial-gradient(900px 500px at 85% -10%,rgba(255,45,143,.16),transparent 60%),radial-gradient(800px 480px at -5% 110%,rgba(255,45,143,.10),transparent 60%),radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.65) 100%)}
.wrap{width:min(1060px,calc(100% - 32px));margin:0 auto}
.site-head{display:flex;align-items:center;justify-content:space-between;gap:16px;padding:20px 0;border-bottom:1px solid var(--line)}
.brand{display:flex;align-items:center;gap:10px;font-weight:700;letter-spacing:.08em;text-transform:uppercase;color:var(--ink);text-decoration:none}
.crown-mark{width:34px;height:34px;flex:0 0 34px;fill:var(--pink)}
.site-nav{display:flex;flex-wrap:wrap;gap:18px}
.site-nav a{color:var(--mute);text-decoration:none;font-size:.95rem}
.site-nav a:hover{color:var(--pink)}
h1{font-size:clamp(2rem,5vw,3.4rem);line-height:1.1;margin:48px 0 16px}
h2{font-size:clamp(1.4rem,3vw,2rem);margin:40px 0 12px}
.tablewrap{width:100%;overflow-x:auto;border:1px solid var(--line);border-radius:12px;background:rgba(255,255,255,.02);margin:24px 0}
table{width:100%;border-collapse:collapse;min-width:480px}
th,td{padding:12px 14px;text-align:left;border-bottom:1px solid var(--line);font-size:.95rem}
th{color:var(--pink);font-weight:600;text-transform:uppercase;font-size:.78rem;letter-spacing:.08em}
.panel{border:1px solid rgba(255,45,143,.35);border-radius:14px;padding:24px;background:rgba(255,255,255,.025)}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin:20px 0}
.chip{border:1px solid var(--line);border-radius:999px;padding:6px 14px;font-size:.85rem;color:var(--ink)}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
@media (max-width:700px){.site-head{flex-direction:column;align-items:flex-start}.grid{grid-template-columns:1fr}}
</style>
