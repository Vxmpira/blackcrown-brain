# Copy: Write the watcher style element only from style to style

Date: 2026-10-30
Task: Write the Watcher style element only, from <style> to </style>, under 30 lines, no script.
For [[Herald]].

<style>
:root{--ink:#e9ecf3;--mute:#9aa3b8;--pink:#ff2d8f;--blue:#2d7bff;--line:rgba(255,255,255,.08)}
*{box-sizing:border-box}
html,body{margin:0;background:#0a0b10;color:var(--ink);font:16px/1.6 system-ui,-apple-system,"Segoe UI",sans-serif}
body{min-height:100vh;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background:radial-gradient(60rem 40rem at 85% -10%,rgba(255,45,143,.22),transparent 60%),radial-gradient(50rem 36rem at 5% 20%,rgba(45,123,255,.18),transparent 60%),repeating-linear-gradient(0deg,rgba(255,255,255,.015) 0 1px,transparent 1px 56px),repeating-linear-gradient(90deg,rgba(255,255,255,.015) 0 1px,transparent 1px 56px),#0a0b10}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background:radial-gradient(120% 90% at 50% 50%,transparent 55%,rgba(0,0,0,.65) 100%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
h1,h2{line-height:1.15;margin:0 0 .5em;font-weight:700;letter-spacing:-.01em}
h1{font-size:clamp(2rem,5vw,3.4rem)}
h2{font-size:clamp(1.4rem,3vw,2rem)}
p,ul{max-width:68ch;color:var(--mute)}
.hero{padding:clamp(56px,10vw,120px) 0 clamp(32px,6vw,64px)}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:20px 0}
.chip{border:1px solid var(--line);background:rgba(255,255,255,.03);border-radius:999px;padding:6px 12px;font-size:.85rem;color:var(--ink)}
.panel{border:1px solid var(--line);background:linear-gradient(180deg,rgba(255,255,255,.04),rgba(255,255,255,.01));border-radius:14px;padding:clamp(18px,3vw,28px)}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin:24px 0}
.stat{font-size:clamp(1.6rem,4vw,2.4rem);font-weight:700;color:var(--ink)}
.stat small{display:block;font-size:.8rem;color:var(--mute);font-weight:400}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
</style>
