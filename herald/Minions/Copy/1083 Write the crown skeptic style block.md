# Copy: Write the crown skeptic style block only under 25 lines

Date: 2026-10-30
Task: Write the Crown skeptic style block only. Under 25 lines, no inline script. Ends with the closing style tag. Return raw CSS in a style element, no code fences.
For [[Herald]].

<style>
:root{--bg:#07070b;--accent:#ff2d8f;--text:#ecebf2;--muted:rgba(236,235,242,.68)}
*{box-sizing:border-box}
html,body{margin:0;color:var(--text);font-family:system-ui,-apple-system,"Segoe UI",sans-serif;line-height:1.6}
body{min-height:100vh;position:relative;overflow-x:hidden;background:
radial-gradient(900px 600px at 12% -8%,rgba(255,45,143,.14),transparent 60%),
radial-gradient(800px 560px at 96% 108%,rgba(255,45,143,.10),transparent 60%),
linear-gradient(rgba(255,255,255,.035) 1px,transparent 1px) 0 0/48px 48px,
linear-gradient(90deg,rgba(255,255,255,.035) 1px,transparent 1px) 0 0/48px 48px,
var(--bg)}
body::after{content:"";position:fixed;inset:0;pointer-events:none;background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.6) 100%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
h1{font-size:clamp(2rem,5vw,3.4rem);line-height:1.1;margin:.4em 0 .3em;letter-spacing:-.02em}
h2{font-size:clamp(1.4rem,3vw,2rem);line-height:1.2;margin:1.6em 0 .5em}
.prose{max-width:70ch}
.prose p{margin:0 0 1em;color:var(--muted)}
.accent{color:var(--accent)}
.grid{display:grid;grid-template-columns:repeat(2,1fr);gap:clamp(12px,2vw,20px)}
.card{border:1px solid rgba(255,45,143,.22);border-radius:12px;padding:clamp(16px,2.5vw,24px);background:rgba(12,12,18,.7)}
.chip{display:inline-block;padding:.25em .7em;border:1px solid rgba(255,45,143,.4);border-radius:999px;font-size:.8rem;color:var(--text)}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
</style>
