# Copy: Write the watcher style block only opening style tag to

Date: 2026-10-30
Task: Write the Watcher style block only, opening style tag to closing style tag, under 40 lines, no inline script.
For [[Herald]].

<style>
:root{--bg:#07060b;--ink:#ece9f4;--mute:#9c97ab;--pink:#ff2d8f;--violet:#7b5cff;--line:rgba(255,255,255,.08);--panel:rgba(18,15,26,.72)}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{background:var(--bg);color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6;min-height:100vh;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-3;pointer-events:none;background:radial-gradient(900px 600px at 15% -10%,rgba(255,45,143,.16),transparent 60%),radial-gradient(800px 560px at 95% 10%,rgba(123,92,255,.12),transparent 62%),radial-gradient(700px 500px at 50% 110%,rgba(255,45,143,.08),transparent 65%)}
body::after{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:56px 56px}
.vignette{position:fixed;inset:0;z-index:-1;pointer-events:none;background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.55) 100%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
h1{font-size:clamp(1.9rem,5vw,3.2rem);line-height:1.15;margin:.6em 0 .4em;letter-spacing:-.01em}
h2{font-size:clamp(1.3rem,3vw,1.8rem);margin:1.6em 0 .5em}
p,li{max-width:75ch;color:var(--mute)}
.grid{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:clamp(12px,2vw,20px)}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
.panel{background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:clamp(18px,3vw,26px);box-shadow:0 0 0 1px rgba(255,45,143,.04) inset}
.chip{display:inline-block;font-size:.78rem;padding:.3em .7em;border-radius:999px;border:1px solid rgba(255,45,143,.35);color:var(--ink);background:rgba(255,45,143,.08);margin:0 .35em .4em 0}
header{display:flex;align-items:center;gap:12px;padding:20px 0}
header svg{width:36px;height:36px;flex:0 0 36px;fill:var(--pink)}
</style>
