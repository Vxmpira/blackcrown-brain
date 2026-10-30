# Copy: Write only the watcher style block one style element under

Date: 2026-10-30
Task: Write only the Watcher style block: one style element, under 40 lines, no script. Return raw CSS and end with the closing style tag.
For [[Herald]].

<style>
:root{--bg:#07060c;--ink:#e9e6f0;--mute:#9a95a8;--pink:#ff2d8f;--violet:#7a5cff;--line:rgba(255,255,255,.08)}
*{box-sizing:border-box}
html,body{margin:0;background:var(--bg);color:var(--ink);font:16px/1.6 system-ui,-apple-system,"Segoe UI",sans-serif}
body{position:relative;min-height:100vh;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background:radial-gradient(60vw 45vh at 12% 8%,rgba(255,45,143,.14),transparent 70%),radial-gradient(55vw 50vh at 88% 18%,rgba(122,92,255,.16),transparent 70%),radial-gradient(70vw 55vh at 50% 110%,rgba(122,92,255,.10),transparent 70%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px),radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.65) 100%);background-size:56px 56px,56px 56px,100% 100%}
.wrap{width:min(1060px,calc(100% - 40px));margin:0 auto}
h1{font-size:clamp(2rem,5vw,3.6rem);line-height:1.08;letter-spacing:-.02em;margin:0 0 .5em}
h2{font-size:clamp(1.4rem,3vw,2rem);line-height:1.2;margin:0 0 .6em}
a{color:var(--violet)}
.hero{padding:clamp(56px,10vw,120px) 0 40px}
.hero p{color:var(--mute);max-width:75ch;font-size:clamp(1rem,2vw,1.15rem);margin:0}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:20px 0}
.chips span{border:1px solid var(--line);border-radius:999px;padding:6px 12px;font-size:.85rem;color:var(--mute);background:rgba(255,255,255,.02)}
.cta{display:inline-block;background:var(--pink);color:#07060c;padding:12px 20px;border-radius:8px;text-decoration:none;font-weight:600}
.cta.ghost{background:transparent;color:var(--ink);border:1px solid var(--violet)}
.fine{font-size:.8rem;color:var(--mute);max-width:75ch;margin:16px 0 0}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
.card{border:1px solid var(--line);border-radius:12px;padding:20px;background:rgba(255,255,255,.015)}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
</style>
