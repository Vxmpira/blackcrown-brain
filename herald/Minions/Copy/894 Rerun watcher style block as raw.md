# Copy: Rerun watcher style block as raw css under 700 characters

Date: 2026-10-30
Task: Rerun Watcher style block as raw CSS, under 700 characters, ending with closing style tag.
For [[Herald]].

<style>
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{background:#07080c;color:#e8e8ee;font-family:system-ui,-apple-system,"Segoe UI",sans-serif;line-height:1.6;min-height:100vh;position:relative;overflow-x:hidden}
body:before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background:radial-gradient(60% 40% at 15% 0%,rgba(120,90,255,.18),transparent 70%),radial-gradient(50% 35% at 90% 10%,rgba(0,190,255,.12),transparent 70%)}
body:after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:56px 56px;box-shadow:inset 0 0 180px rgba(0,0,0,.85)}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
h1{font-size:clamp(1.8rem,4.5vw,3rem);line-height:1.15;margin:0 0 .5em}
h2{font-size:clamp(1.3rem,3vw,1.9rem);margin:1.6em 0 .5em}
p,ul{max-width:75ch}
table,figure{width:100%}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
</style>
