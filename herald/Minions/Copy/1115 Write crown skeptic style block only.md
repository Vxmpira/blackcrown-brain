# Copy: Write crown skeptic style block only under 40 lines no

Date: 2026-10-30
Task: Write Crown skeptic style block only, under 40 lines, no script, no body tags, closing style tag required.
For [[Herald]].

<style>
:root{--bg:#07080c;--ink:#e8e9ee;--mute:#9aa0ad;--line:rgba(255,255,255,.08);--gold:#c9a64b;--panel:#0e1118}
*{box-sizing:border-box}
body{margin:0;min-height:100vh;background:var(--bg);color:var(--ink);font:16px/1.6 system-ui,-apple-system,"Segoe UI",sans-serif;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background:radial-gradient(60% 40% at 12% 0%,rgba(201,166,75,.10),transparent 70%),radial-gradient(50% 35% at 92% 8%,rgba(90,120,255,.08),transparent 70%),radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.65) 100%)}
body::after{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background-image:linear-gradient(var(--line) 1px,transparent 1px),linear-gradient(90deg,var(--line) 1px,transparent 1px);background-size:48px 48px;opacity:.35}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
h1{font-size:clamp(28px,5vw,52px);line-height:1.1;margin:0 0 16px;letter-spacing:-.01em}
h2{font-size:clamp(20px,3vw,28px);line-height:1.2;margin:36px 0 12px}
.prose{max-width:62ch}
.prose p{margin:0 0 14px;color:var(--mute)}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:18px 0}
.chip{border:1px solid var(--line);border-radius:999px;padding:6px 12px;font-size:13px;color:var(--mute)}
.panel{background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:20px}
.panel strong{display:block;color:var(--gold);font-size:14px;margin-bottom:6px}
.rooms{display:grid;grid-template-columns:repeat(4,1fr);gap:16px;margin:24px 0}
.rooms .panel{min-height:120px}
.split{display:grid;grid-template-columns:1fr 1fr;gap:16px;margin:24px 0}
@media (max-width:700px){.wrap{padding:0 16px}.rooms,.split{grid-template-columns:1fr}.rooms{gap:12px}}
</style>
