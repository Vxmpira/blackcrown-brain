# Copy: Rewrite crown skeptic style block one style tag under 40

Date: 2026-11-11
Task: Rewrite Crown skeptic style block: one style tag, under 40 lines, closed, no inline script.
For [[Herald]].

<style>
:root{--bg:#0b0b12;--ink:#e8e8ee;--pink:#ff2d8f;--muted:#9a9aa8}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{background:var(--bg);color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",sans-serif;line-height:1.6;min-height:100vh;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background:radial-gradient(60% 45% at 15% 0%,rgba(255,45,143,.14),transparent 70%),radial-gradient(55% 40% at 90% 12%,rgba(255,45,143,.08),transparent 70%),radial-gradient(70% 50% at 50% 100%,rgba(255,45,143,.07),transparent 75%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.6) 100%),linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:auto,56px 56px,56px 56px}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
h1{font-size:clamp(1.9rem,5vw,3.2rem);line-height:1.1;margin:0 0 .5em;letter-spacing:-.02em}
h2{font-size:clamp(1.4rem,3.2vw,2rem);margin:1.6em 0 .4em}
p{max-width:68ch;margin:0 0 1em}
a{color:var(--pink);text-decoration:none}
a:hover{text-decoration:underline}
.muted{color:var(--muted)}
.chip{display:inline-block;border:1px solid rgba(255,45,143,.45);color:var(--pink);border-radius:999px;padding:.2em .75em;font-size:.8rem;margin:0 .4em .4em 0}
.panel{border:1px solid rgba(255,255,255,.08);background:rgba(255,255,255,.02);border-radius:12px;padding:clamp(16px,3vw,24px);margin:1.2em 0}
.tablewrap{width:100%;overflow-x:auto;border:1px solid rgba(255,255,255,.08);border-radius:12px;margin:1.2em 0}
table{width:100%;border-collapse:collapse;min-width:520px}
th,td{text-align:left;padding:.7em .9em;border-bottom:1px solid rgba(255,255,255,.06)}
th{color:var(--muted);font-weight:600;font-size:.85rem}
@media (max-width:700px){.grid{grid-template-columns:1fr!important}}
</style>
