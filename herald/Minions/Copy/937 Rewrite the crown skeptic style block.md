# Copy: Rewrite the crown skeptic style block only opening style tag

Date: 2026-10-30
Task: Rewrite the Crown skeptic style block only, opening style tag to closing style tag, under 40 lines, no inline script. Previous return was empty.
For [[Herald]].

<style>
:root{--bg:#07080c;--ink:#e7e9ef;--mute:#9aa1b2;--line:rgba(255,255,255,.08);--acc:#7c6cff;--acc2:#2bd4c4}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{background:linear-gradient(180deg,#0b0d14 0%,var(--bg) 60%,#06070a 100%);color:var(--ink);font:16px/1.6 system-ui,-apple-system,"Segoe UI",sans-serif;min-height:100vh;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:0;pointer-events:none;background:radial-gradient(900px 600px at 15% 0%,rgba(124,108,255,.22),transparent 60%),radial-gradient(700px 500px at 90% 20%,rgba(43,212,196,.12),transparent 60%),radial-gradient(600px 500px at 50% 110%,rgba(124,108,255,.14),transparent 65%),linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px),radial-gradient(ellipse at center,transparent 45%,rgba(0,0,0,.65) 100%);background-size:auto,auto,auto,auto,56px 56px,56px 56px,auto}
body>*{position:relative;z-index:1}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
header .wrap{display:flex;align-items:center;gap:12px;padding-top:24px}
header svg{width:36px;height:36px;flex:none}
h1{font-size:clamp(28px,5vw,52px);line-height:1.1;margin:48px 0 16px;letter-spacing:-.02em}
h2{font-size:clamp(20px,3vw,28px);margin:40px 0 12px}
p,li{max-width:75ch;color:var(--mute)}
p strong{color:var(--ink)}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin:32px 0}
.panel{background:rgba(255,255,255,.03);border:1px solid var(--line);border-radius:14px;padding:22px}
.panel h3{margin:0 0 8px;font-size:18px}
.panel p{margin:0;font-size:15px}
.chip{display:inline-block;font-size:12px;letter-spacing:.06em;text-transform:uppercase;padding:6px 10px;border:1px solid var(--line);border-radius:999px;color:var(--ink);background:rgba(124,108,255,.1);margin:0 6px 8px 0}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
</style>
