# Copy: Write the crown skeptic style block only under 30 lines

Date: 2026-10-30
Task: Write the Crown skeptic style block only: under 30 lines, no inline script, dark pink accent #ff2d8f on near-black, body background with soft radial glows and a
For [[Herald]].

<style>
:root{--ink:#07070b;--pink:#ff2d8f;--text:#ecebf2;--mute:#9a97a8}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{
min-height:100vh;
color:var(--text);
font:16px/1.6 system-ui,-apple-system,"Segoe UI",sans-serif;
background:
radial-gradient(900px 520px at 12% -8%,rgba(255,45,143,.20),transparent 62%),
radial-gradient(760px 460px at 96% 12%,rgba(255,45,143,.11),transparent 60%),
linear-gradient(rgba(255,255,255,.035) 1px,transparent 1px) 0 0/48px 48px,
linear-gradient(90deg,rgba(255,255,255,.035) 1px,transparent 1px) 0 0/48px 48px,
var(--ink);
}
body::after{content:"";position:fixed;inset:0;pointer-events:none;background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.72) 100%)}
.wrap{width:min(1060px,92%);margin:0 auto;position:relative;z-index:1}
h1{font-size:clamp(28px,5vw,52px);line-height:1.1;margin:0 0 16px}
h1 span,a{color:var(--pink)}
p{max-width:65ch;color:var(--mute)}
.chip{display:inline-block;border:1px solid var(--pink);color:var(--pink);padding:4px 10px;border-radius:999px;font-size:13px;margin:4px 6px 4px 0}
.grid{display:grid;grid-template-columns:repeat(2,1fr);gap:16px}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
</style>
