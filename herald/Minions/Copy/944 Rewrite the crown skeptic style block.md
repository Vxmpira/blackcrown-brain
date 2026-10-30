# Copy: Rewrite the crown skeptic style block opening style tag through

Date: 2026-10-30
Task: Rewrite the Crown skeptic style block, opening style tag through closing style tag, 25 lines or fewer, no script
For [[Herald]].

<style>
:root{--bg:#07060b;--text:#ece9f4;--muted:#9c97ab;--pink:#ff2d8f;--violet:#7b5cff}
*{box-sizing:border-box}
html,body{margin:0;background:var(--bg);color:var(--text);font-family:system-ui,-apple-system,"Segoe UI",sans-serif;line-height:1.6}
body{position:relative;min-height:100vh;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background:radial-gradient(60rem 40rem at 15% -10%,rgba(255,45,143,.14),transparent 60%),radial-gradient(50rem 36rem at 95% 10%,rgba(123,92,255,.16),transparent 60%),linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:auto,auto,56px 56px,56px 56px}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.7) 100%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(1rem,4vw,2rem)}
h1,h2{line-height:1.15;margin:0 0 .6em;font-weight:700}
h1{font-size:clamp(1.9rem,5vw,3.2rem)}
h2{font-size:clamp(1.3rem,3vw,1.8rem)}
.prose{max-width:75ch}
.prose p{margin:0 0 1em}
.muted{color:var(--muted)}
.accent{color:var(--pink)}
.chips{display:flex;flex-wrap:wrap;gap:.5rem;margin:1.5rem 0}
.chip{border:1px solid rgba(255,45,143,.45);padding:.35rem .8rem;border-radius:999px;font-size:.9rem;background:rgba(255,255,255,.02)}
.chip:nth-child(even){border-color:rgba(123,92,255,.55)}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:1rem;margin:1.5rem 0}
.card{border:1px solid rgba(255,255,255,.08);border-radius:12px;padding:1.2rem;background:rgba(255,255,255,.02)}
.card strong{display:block;margin-bottom:.3rem}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
</style>
