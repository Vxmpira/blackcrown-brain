# Copy: Write watcher style block only under 40 lines

Date: 2026-11-01
Task: Write Watcher style block only, under 40 lines.
For [[Herald]].

<style>
:root{--accent:#ff2d8f;--ink:#f2f2f5;--mute:#9a9aa8;--line:rgba(255,255,255,.08);--panel:#12121a}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6;min-height:100vh;background-color:#0a0a10;background-image:radial-gradient(60vw 40vw at 85% -5%,rgba(255,45,143,.18),transparent 70%),radial-gradient(50vw 35vw at -10% 110%,rgba(255,45,143,.12),transparent 70%),linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:auto,auto,56px 56px,56px 56px;background-attachment:fixed}
body::after{content:"";position:fixed;inset:0;pointer-events:none;background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.55) 100%)}
.site-header,.hero,.grid{width:100%;max-width:1060px;margin:0 auto;padding-left:20px;padding-right:20px}
.site-header{display:flex;align-items:center;justify-content:space-between;gap:16px;padding-top:24px;padding-bottom:24px;border-bottom:1px solid var(--line)}
.brand{display:flex;align-items:center;gap:12px;color:var(--ink);text-decoration:none}
.brand svg{width:32px;height:32px;fill:var(--accent)}
.brand-name{font-weight:700;letter-spacing:.14em;text-transform:uppercase;font-size:clamp(.8rem,2vw,.95rem)}
.hero{padding-top:clamp(48px,10vw,110px);padding-bottom:clamp(40px,8vw,80px)}
.hero h1{font-size:clamp(2rem,6vw,3.6rem);line-height:1.1;margin:0 0 20px;letter-spacing:-.02em}
.hero h1 span{color:var(--accent)}
.hero p{max-width:68ch;color:var(--mute);font-size:clamp(1rem,2.2vw,1.125rem);margin:0 0 28px}
.cta{display:inline-block;padding:14px 26px;background:var(--accent);color:#0a0a10;font-weight:700;text-decoration:none;border-radius:6px}
.cta:hover{background:#ff5aa6}
.grid{display:grid;grid-template-columns:repeat(2,1fr);gap:20px;padding-bottom:40px}
.panel{background:var(--panel);border:1px solid var(--line);border-radius:10px;padding:24px}
.panel h2{font-size:clamp(1.25rem,3vw,1.6rem);margin:0 0 12px}
.panel p{max-width:68ch;color:var(--mute);margin:0}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:0;padding:0;list-style:none}
.chips li{border:1px solid rgba(255,45,143,.45);color:var(--ink);padding:6px 12px;border-radius:999px;font-size:.85rem}
@media (max-width:700px){.grid{grid-template-columns:1fr}.site-header{flex-direction:column;align-items:flex-start}}
</style>
