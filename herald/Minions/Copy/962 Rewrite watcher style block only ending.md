# Copy: Rewrite watcher style block only ending with closing style tag

Date: 2026-10-30
Task: Rewrite Watcher style block only, ending with closing style tag.
For [[Herald]].

<style>
:root{--bg:#07060b;--pink:#ff2d8f;--violet:#7b5cff;--ink:#ece9f4;--mute:#9a95aa}
*{box-sizing:border-box}
html,body{margin:0;background:var(--bg);color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",sans-serif;line-height:1.6}
body{position:relative;min-height:100vh}
body::before{content:"";position:fixed;inset:0;z-index:-2;background:radial-gradient(circle at 15% 10%,rgba(255,45,143,.14),transparent 45%),radial-gradient(circle at 85% 30%,rgba(123,92,255,.16),transparent 50%),var(--bg)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px),radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.75) 100%);background-size:56px 56px,56px 56px,100% 100%}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
h1{font-size:clamp(1.9rem,5vw,3.2rem);line-height:1.1;margin:.6em 0 .4em}
h2{font-size:clamp(1.3rem,3vw,1.8rem);margin:1.6em 0 .5em}
p,li{max-width:75ch}
.eyebrow{color:var(--pink);text-transform:uppercase;letter-spacing:.14em;font-size:.78rem}
.glow{color:var(--violet)}
.chips{display:flex;flex-wrap:wrap;gap:8px;list-style:none;padding:0;margin:1em 0}
.chip{border:1px solid rgba(123,92,255,.45);border-radius:999px;padding:4px 12px;font-size:.85rem;color:var(--ink)}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
.card{border:1px solid rgba(255,45,143,.25);border-radius:12px;padding:18px;background:rgba(12,10,20,.6)}
.card p{color:var(--mute);margin:.4em 0 0}
.fig{border:1px solid rgba(123,92,255,.3);border-radius:12px;padding:16px;overflow-x:auto;background:rgba(10,8,16,.7)}
table{width:100%;border-collapse:collapse}
th,td{text-align:left;padding:8px;border-bottom:1px solid rgba(255,255,255,.08)}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
</style>
