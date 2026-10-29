# Copy: Rewrite the watcher style block under 40 lines no script

Date: 2026-10-29
Task: Rewrite the Watcher style block under 40 lines, no script, starting with <style> and ending with </style>.
For [[Herald]].

<style>
:root{--accent:#ff2d8f;--second:#3aa0ff;--text:#e9ecf4;--mute:#9aa3b8;--line:rgba(255,255,255,.08)}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{color:var(--text);font:16px/1.6 system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;min-height:100vh;background:radial-gradient(900px 500px at 12% -10%,rgba(255,45,143,.18),transparent 60%),radial-gradient(800px 480px at 95% 8%,rgba(58,160,255,.14),transparent 60%),linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px) 0 0/56px 56px,linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px) 0 0/56px 56px,radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.55) 100%),#0b0d14;background-attachment:fixed}
.site-head{max-width:1060px;margin:0 auto;padding:22px 20px;display:flex;align-items:center;justify-content:space-between;gap:16px;border-bottom:1px solid var(--line)}
.brand{display:flex;align-items:center;gap:10px;font-weight:700;letter-spacing:.04em;color:var(--text);text-decoration:none}
.brand svg{width:34px;height:34px;flex:none}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
h1{font-size:clamp(2rem,5.2vw,3.4rem);line-height:1.08;margin:48px 0 16px;letter-spacing:-.02em}
h1 span{color:var(--accent)}
.lede{max-width:70ch;color:var(--mute);font-size:clamp(1rem,2vw,1.15rem);margin:0 0 24px}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:0 0 32px;padding:0;list-style:none}
.chips li{border:1px solid rgba(58,160,255,.35);color:var(--second);border-radius:999px;padding:6px 12px;font-size:.85rem}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
.panel{background:rgba(18,21,32,.78);border:1px solid var(--line);border-top:2px solid var(--accent);border-radius:14px;padding:22px}
.cta{display:inline-block;background:var(--accent);color:#0b0d14;font-weight:700;text-decoration:none;padding:12px 20px;border-radius:10px}
footer{max-width:1060px;margin:64px auto 0;padding:24px 20px 40px;border-top:1px solid var(--line);color:var(--mute);font-size:.85rem}
@media (max-width:700px){.grid{grid-template-columns:1fr}.site-head{flex-direction:column;align-items:flex-start}}
</style>
