# Copy: Write only the watcher style block as one style element

Date: 2026-10-31
Task: Write only the Watcher style block as one style element, under 40 lines, no script. End with the closing style tag.
For [[Herald]].

<style>
:root{--pink:#ff4fa3;--bg:#07070b;--ink:#e9e9f0;--mute:#9a9aab}
*{box-sizing:border-box}
html,body{margin:0;background:var(--bg);color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",sans-serif}
body{position:relative;min-height:100vh;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:44px 44px}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background:radial-gradient(640px 420px at 12% 8%,rgba(255,79,163,.16),transparent 70%),radial-gradient(560px 380px at 92% 70%,rgba(255,79,163,.10),transparent 70%),radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.6) 100%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,40px)}
h1{font-size:clamp(2rem,5vw,3.4rem);line-height:1.1;margin:0 0 .5em}
h1 span,.accent{color:var(--pink)}
p{max-width:68ch;color:var(--mute);line-height:1.6}
.grid2{display:grid;grid-template-columns:1fr 1fr;gap:clamp(16px,3vw,28px)}
.card{border:1px solid rgba(255,79,163,.22);border-radius:12px;padding:clamp(16px,2.5vw,24px);background:rgba(255,255,255,.02)}
@media (max-width:700px){.grid2{grid-template-columns:1fr}}
</style>
