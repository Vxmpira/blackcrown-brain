# Copy: Return crown skeptic style block under 40 lines no inline

Date: 2026-11-13
Task: Return Crown skeptic style block under 40 lines, no inline script
For [[Herald]].

<style>
:root{--bg:#07070b;--ink:#e9e9ef;--mute:#9a9aab;--pink:#ff4fa3;--line:rgba(255,255,255,.08)}
*{box-sizing:border-box}
html,body{margin:0;background:var(--bg);color:var(--ink);font:16px/1.6 system-ui,-apple-system,"Segoe UI",sans-serif}
body{min-height:100vh;position:relative;overflow-x:hidden;background:
radial-gradient(900px 500px at 12% -10%,rgba(255,79,163,.16),transparent 60%),
radial-gradient(700px 420px at 95% 20%,rgba(255,79,163,.10),transparent 60%),
linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px) 0 0/56px 56px,
linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px) 0 0/56px 56px,
var(--bg)}
body::after{content:"";position:fixed;inset:0;pointer-events:none;background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.55) 100%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px);position:relative;z-index:1}
h1{font-size:clamp(28px,5vw,52px);line-height:1.1;margin:.4em 0 .3em;letter-spacing:-.01em}
h2{font-size:clamp(20px,3vw,28px);margin:1.6em 0 .5em}
.prose{max-width:68ch}
.prose p{margin:0 0 1em;color:var(--mute)}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:1em 0}
.chip{border:1px solid var(--line);border-radius:999px;padding:6px 12px;font-size:13px;color:var(--ink);background:rgba(255,255,255,.03)}
.chip.on{border-color:var(--pink);color:var(--pink)}
.panel{margin:1.5em 0;border:1px solid var(--line);border-radius:14px;background:rgba(255,255,255,.02);padding:clamp(16px,3vw,24px)}
.panel figcaption{font-size:12px;color:var(--mute);margin-top:12px}
.meter{height:10px;border-radius:999px;background:rgba(255,255,255,.06);overflow:hidden}
.meter span{display:block;height:100%;background:linear-gradient(90deg,var(--pink),#ff9ccb)}
.grid{display:grid;grid-template-columns:repeat(2,1fr);gap:16px}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
</style>
