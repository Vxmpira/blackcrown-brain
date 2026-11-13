# Copy: Rewrite the crown skeptic style block only under 40 lines

Date: 2026-11-13
Task: Rewrite the Crown skeptic style block only, under 40 lines, pure CSS, closed with the style tag
For [[Herald]].

<style>
:root{--bg:#0b0912;--ink:#e9e6ef;--muted:#9a95a8;--pink:#ff2d8f;--hair:rgba(255,255,255,.08)}
*{box-sizing:border-box}
html{background:var(--bg)}
html,body{margin:0;color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6}
body{position:relative;min-height:100vh;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background:radial-gradient(60vw 45vw at 12% 8%,rgba(255,45,143,.14),transparent 70%),radial-gradient(50vw 40vw at 88% 30%,rgba(120,80,255,.12),transparent 70%),radial-gradient(55vw 42vw at 40% 95%,rgba(255,45,143,.08),transparent 70%),var(--bg)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px) 0 0/56px 56px,linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px) 0 0/56px 56px,radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.55) 100%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
h1{font-size:clamp(1.9rem,5vw,3.2rem);line-height:1.12;margin:.4em 0 .3em}
h2{font-size:clamp(1.4rem,3.4vw,2.1rem);line-height:1.2;margin:1.6em 0 .5em}
p{max-width:68ch}
.muted{color:var(--muted)}
.accent{color:var(--pink)}
.hair{border-top:1px solid var(--hair)}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:16px 0}
.chip{border:1px solid var(--hair);border-radius:999px;padding:6px 12px;font-size:.9rem;color:var(--muted);background:rgba(255,255,255,.02)}
.chip.on{border-color:rgba(255,45,143,.5);color:var(--ink)}
.grid{display:grid;grid-template-columns:repeat(2,1fr);gap:16px}
.card{border:1px solid var(--hair);border-radius:14px;padding:clamp(16px,3vw,24px);background:rgba(255,255,255,.02)}
.tablewrap{width:100%;overflow-x:auto;border:1px solid var(--hair);border-radius:12px}
table{width:100%;border-collapse:collapse}
th,td{padding:10px 12px;text-align:left;border-bottom:1px solid var(--hair)}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
</style>
