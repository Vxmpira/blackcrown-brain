# Copy: Rewrite the watcher style block opening style tag through closing

Date: 2026-10-30
Task: Rewrite the Watcher style block: opening style tag through closing style tag, 40 lines or fewer, no code fences.
For [[Herald]].

<style>
:root{--bg:#07060b;--text:#ece9f4;--muted:#9c97ab;--pink:#ff2d8f;--violet:#7b5cff}
*,*::before,*::after{box-sizing:border-box}
html{background:var(--bg)}
body{margin:0;min-height:100vh;position:relative;overflow-x:hidden;background:var(--bg);color:var(--text);font:16px/1.6 system-ui,-apple-system,"Segoe UI",Roboto,sans-serif}
body::before{content:"";position:fixed;inset:0;z-index:0;pointer-events:none;background:radial-gradient(60rem 40rem at 85% -10%,rgba(255,45,143,.16),transparent 60%),radial-gradient(55rem 42rem at -10% 40%,rgba(123,92,255,.18),transparent 60%)}
body::after{content:"";position:fixed;inset:0;z-index:0;pointer-events:none;background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.72) 100%),linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:100% 100%,56px 56px,56px 56px}
.wrap{position:relative;z-index:1;width:min(1060px,calc(100% - 2.5rem));margin:0 auto}
h1{font-size:clamp(2rem,5vw,3.4rem);line-height:1.1;letter-spacing:-.01em;margin:.6em 0 .4em}
h2{font-size:clamp(1.4rem,3vw,2rem);line-height:1.2;margin:1.6em 0 .5em}
p{max-width:65ch;margin:0 0 1em}
.muted{color:var(--muted)}
.accent{color:var(--pink)}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:1rem}
.card{border:1px solid rgba(255,255,255,.08);background:rgba(20,18,30,.6);border-radius:14px;padding:1.2rem}
.chip{display:inline-block;padding:.25rem .65rem;border:1px solid rgba(123,92,255,.5);border-radius:999px;font-size:.8rem;color:var(--muted)}
.fig{width:100%;overflow-x:auto;border:1px solid rgba(255,255,255,.08);border-radius:14px;background:rgba(12,10,18,.7);padding:1rem}
@media (max-width:700px){.grid{grid-template-columns:1fr}.wrap{width:calc(100% - 2rem)}}
</style>
