# Copy: Rebuild watcher page style block only under 40 lines no

Date: 2026-11-13
Task: Rebuild Watcher page style block only, under 40 lines, no inline script, ends with closing style tag
For [[Herald]].

<style>
:root{--accent:#ff2d8f;--ink:#e9e9ef;--mute:#9a9aa8;--line:rgba(255,255,255,.08);--card:#12121a}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{min-height:100vh;color:var(--ink);font:16px/1.6 system-ui,-apple-system,"Segoe UI",sans-serif;position:relative;overflow-x:hidden;background:radial-gradient(900px 500px at 15% -10%,rgba(255,45,143,.14),transparent 60%),radial-gradient(800px 480px at 95% 10%,rgba(255,45,143,.08),transparent 60%),linear-gradient(180deg,#0d0d14,#09090e)}
body::before{content:"";position:fixed;inset:0;pointer-events:none;z-index:-1;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:56px 56px}
body::after{content:"";position:fixed;inset:0;pointer-events:none;z-index:-1;background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.55) 100%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
header{display:flex;align-items:center;justify-content:space-between;gap:16px;padding:20px 0;border-bottom:1px solid var(--line)}
.brand{display:flex;align-items:center;gap:10px;font-weight:700;letter-spacing:.04em;color:var(--ink);text-decoration:none}
.brand svg{width:28px;height:28px;color:var(--accent)}
h1{font-size:clamp(28px,5vw,52px);line-height:1.1;margin:40px 0 12px;letter-spacing:-.01em}
h2{font-size:clamp(20px,3vw,28px);margin:48px 0 12px}
p,li{max-width:68ch;color:var(--mute)}
.accent{color:var(--accent)}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:20px 0}
.chip{border:1px solid rgba(255,45,143,.35);color:var(--ink);padding:6px 12px;border-radius:999px;font-size:13px;background:rgba(255,45,143,.06)}
.figure{width:100%;margin:28px 0;border:1px solid var(--line);border-radius:14px;background:var(--card);padding:clamp(16px,3vw,24px)}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin:28px 0}
.tablewrap{width:100%;overflow-x:auto;border:1px solid var(--line);border-radius:12px;margin:24px 0}
table{width:100%;border-collapse:collapse;font-size:14px}
th,td{padding:12px 14px;text-align:left;border-bottom:1px solid var(--line)}
th{color:var(--ink)}
td{color:var(--mute)}
.illus{font-size:12px;color:var(--mute);text-transform:uppercase;letter-spacing:.12em}
footer{margin:64px 0 32px;padding-top:20px;border-top:1px solid var(--line);color:var(--mute);font-size:13px}
@media (max-width:700px){.grid{grid-template-columns:1fr}header{flex-direction:column;align-items:flex-start}}
</style>
