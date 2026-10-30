# Copy: Rewrite the crown skeptic style block only under 40 lines

Date: 2026-10-30
Task: Rewrite the Crown skeptic style block only: under 40 lines, no inline script, must end with a closing style tag. Return the complete block, no fences.
For [[Herald]].

<style>
:root{--accent:#ff2d8f;--bg:#07060a;--ink:#ece9f2;--muted:#9a95a6}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{background:var(--bg);color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6;min-height:100vh;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background:radial-gradient(circle at 12% 8%,rgba(255,45,143,.16),transparent 40%),radial-gradient(circle at 88% 34%,rgba(255,45,143,.10),transparent 45%),radial-gradient(circle at 50% 100%,rgba(255,45,143,.09),transparent 50%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px) 0 0/56px 56px,linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px) 0 0/56px 56px,radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.65) 100%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
h1,h2,h3{line-height:1.15;margin:0 0 .5em}
h1{font-size:clamp(1.9rem,4.2vw,3.2rem)}
h2{font-size:clamp(1.4rem,3vw,2.2rem)}
h3{font-size:1.05rem;color:var(--accent)}
p{max-width:75ch;margin:0 0 1em}
.muted{color:var(--muted)}
.accent{color:var(--accent)}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin:20px 0}
.chip{border:1px solid rgba(255,45,143,.45);background:rgba(255,45,143,.06);border-radius:999px;padding:6px 14px;font-size:.9rem}
.skeptic-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:20px}
.card{border:1px solid rgba(236,233,242,.12);background:rgba(7,6,10,.7);border-radius:12px;padding:24px}
.claim{border-left:2px solid var(--accent);padding-left:16px}
.illus{font-size:.8rem;color:var(--muted);text-transform:uppercase;letter-spacing:.08em}
@media (max-width:699px){.skeptic-grid{grid-template-columns:1fr}}
</style>
