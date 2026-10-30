# Copy: Rewrite the complete crown skeptic style block starting with style

Date: 2026-10-30
Task: Rewrite the complete Crown skeptic style block, starting with style and ending with the closing style tag, under 40 lines, no script.
For [[Herald]].

<style>
:root{--pink:#ff2d8f;--ink:#e9e9f0;--muted:#9a9aaa;--hair:rgba(255,255,255,.08)}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{
  color:var(--ink);
  font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;
  line-height:1.6;
  background-color:#07070b;
  background-image:
    radial-gradient(60% 50% at 15% 0%,rgba(255,45,143,.18),transparent 70%),
    radial-gradient(45% 40% at 90% 30%,rgba(255,45,143,.12),transparent 70%),
    radial-gradient(50% 45% at 50% 100%,rgba(255,45,143,.10),transparent 70%),
    linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),
    linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px),
    radial-gradient(120% 90% at 50% 50%,transparent 55%,rgba(0,0,0,.65) 100%);
  background-size:auto,auto,auto,56px 56px,56px 56px,auto;
  background-attachment:fixed;
  min-height:100vh;
}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(18px,4vw,32px)}
h1,h2{font-weight:700;letter-spacing:-.01em;line-height:1.15;margin:0 0 .6em}
h1{font-size:clamp(2rem,4.2vw,3.4rem)}
h2{font-size:clamp(1.4rem,2.6vw,2rem)}
.lede,p,li{max-width:75ch}
p{margin:0 0 1em}
.muted{color:var(--muted)}
.hair{border:0;border-top:1px solid var(--hair);margin:2.5rem 0}
.accent{color:var(--pink)}
.chips{display:flex;flex-wrap:wrap;gap:.5rem}
.chip{border:1px solid var(--hair);padding:.35rem .75rem;border-radius:999px;font-size:.9rem;color:var(--muted)}
.grid{display:grid;grid-template-columns:repeat(2,1fr);gap:1rem}
.card{border:1px solid var(--hair);border-radius:12px;padding:1.25rem;background:rgba(255,255,255,.015)}
.card h3{color:var(--pink);margin:0 0 .4rem;font-size:1.05rem}
.btn{display:inline-block;background:var(--pink);color:#0a0a0f;padding:.8rem 1.2rem;border-radius:8px;font-weight:600;text-decoration:none}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
</style>
