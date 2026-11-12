# Copy: Write crown skeptic style block raw css inside a style

Date: 2026-11-11
Task: Write Crown skeptic style block: raw CSS inside a style tag, under 40 lines, no script.
For [[Herald]].

<style>
*{box-sizing:border-box;margin:0;padding:0}
:root{--pink:#ff2d8f;--ink:#e8ecf2;--mute:#8a94a6;--line:rgba(255,255,255,.08)}
html,body{min-height:100%}
body{background:#07090d;color:var(--ink);font:16px/1.6 system-ui,-apple-system,"Segoe UI",sans-serif;-webkit-font-smoothing:antialiased;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;background:radial-gradient(60vw 40vw at 85% 0%,rgba(255,45,143,.14),transparent 70%),radial-gradient(50vw 40vw at 0% 100%,rgba(70,120,200,.12),transparent 70%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px),radial-gradient(ellipse at center,transparent 45%,rgba(0,0,0,.65) 100%);background-size:56px 56px,56px 56px,100% 100%}
.wrap{width:min(1060px,100% - 40px);margin:0 auto}
header svg{width:44px;height:44px;display:block;color:var(--pink)}
h1,h2{font-weight:700;letter-spacing:-.02em;line-height:1.1}
h1{font-size:clamp(2rem,5vw,3.4rem);margin:1.5rem 0 1rem}
h2{font-size:clamp(1.4rem,3vw,2rem);margin-bottom:.6rem}
p{max-width:68ch;color:var(--mute)}
.chips{display:flex;flex-wrap:wrap;gap:.5rem;margin:1.2rem 0}
.chips span{border:1px solid var(--line);border-radius:999px;padding:.35rem .8rem;font-size:.85rem;background:rgba(255,255,255,.02)}
.grid{display:grid;grid-template-columns:repeat(2,1fr);gap:1rem;margin-top:2rem}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
.site-foot{border-top:1px solid var(--line);margin-top:4rem;padding:2rem 0 3rem}
.foot-row{display:flex;flex-wrap:wrap;justify-content:space-between;gap:1rem;align-items:center}
.foot-name{font-weight:700}
.foot-note{color:var(--mute);font-size:.85rem;max-width:60ch}
.foot-link{color:var(--ink);text-decoration:none;border-bottom:1px solid var(--pink)}
.foot-link:hover{color:var(--pink)}
a:focus-visible{outline:2px solid var(--pink);outline-offset:3px}
</style>
