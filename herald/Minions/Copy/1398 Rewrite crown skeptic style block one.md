# Copy: Rewrite crown skeptic style block one style tag under 40

Date: 2026-11-11
Task: Rewrite Crown skeptic style block: one style tag, under 40 lines, closed, no inline script.
For [[Herald]].

<style>
:root{--pink:#ff2d8f;--ink:#e8e8ee;--mute:#9a9aa8;--line:rgba(255,255,255,.08);--panel:rgba(255,255,255,.03)}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{background:#0b0b12;color:var(--ink);font:16px/1.6 system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;min-height:100vh;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background:radial-gradient(60vmax 40vmax at 85% -5%,rgba(255,45,143,.18),transparent 60%),radial-gradient(50vmax 35vmax at -10% 110%,rgba(120,80,255,.14),transparent 60%),radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.6) 100%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:56px 56px}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
.header{border-bottom:1px solid var(--line);padding:18px 0}
.header .wrap{display:flex;align-items:center;justify-content:space-between;gap:16px;flex-wrap:wrap}
.hero{padding:clamp(48px,9vw,96px) 0 clamp(32px,6vw,64px)}
.hero h1{font-size:clamp(28px,5.2vw,52px);line-height:1.12;margin:0 0 16px;letter-spacing:-.01em}
.hero h1 span{color:var(--pink)}
.hero p{max-width:75ch;color:var(--mute);margin:0}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin-top:24px}
.chip{border:1px solid var(--line);background:var(--panel);border-radius:999px;padding:6px 14px;font-size:14px;color:var(--ink)}
.chip b{color:var(--pink);font-weight:600}
.main{padding:0 0 clamp(48px,8vw,80px)}
.main section{padding:28px 0;border-top:1px solid var(--line)}
.main h2{font-size:clamp(20px,3vw,28px);margin:0 0 12px}
.main p{max-width:75ch;margin:0 0 14px}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
.card{border:1px solid var(--line);background:var(--panel);border-radius:14px;padding:20px}
.tablewrap{width:100%;overflow-x:auto;border:1px solid var(--line);border-radius:12px}
.tablewrap table{width:100%;border-collapse:collapse;min-width:520px}
.tablewrap th,.tablewrap td{text-align:left;padding:12px 14px;border-bottom:1px solid var(--line)}
.tablewrap th{color:var(--mute);font-weight:600;font-size:14px}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
</style>
