# Copy: Write crown skeptic style block complete ending with closing style

Date: 2026-11-01
Task: Write Crown skeptic style block, complete, ending with closing style tag.
For [[Herald]].

<style>
:root{--bg:#07090d;--ink:#e8ebf0;--mute:#9aa3b2;--line:rgba(255,255,255,.08);--acc:#7c8cff;--acc2:#3fd1c4}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{background:var(--bg);color:var(--ink);font:16px/1.6 system-ui,-apple-system,"Segoe UI",sans-serif;min-height:100vh;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background:radial-gradient(900px 600px at 15% -10%,rgba(124,140,255,.16),transparent 60%),radial-gradient(800px 560px at 95% 10%,rgba(63,209,196,.10),transparent 60%),var(--bg)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px),radial-gradient(ellipse at center,transparent 45%,rgba(0,0,0,.65) 100%);background-size:56px 56px,56px 56px,100% 100%}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
h1{font-size:clamp(28px,5vw,46px);line-height:1.15;margin:0 0 .5em;letter-spacing:-.01em}
h2{font-size:clamp(20px,3vw,26px);margin:1.6em 0 .5em}
p{max-width:75ch;margin:0 0 1em;color:var(--mute)}
.lede{color:var(--ink)}
.grid{display:grid;grid-template-columns:1fr 1fr;gap:20px;margin-top:28px}
.card{border:1px solid var(--line);border-radius:14px;padding:22px;background:rgba(12,15,22,.6)}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin:18px 0}
.chips span{font-size:13px;padding:7px 14px;border-radius:999px;border:1px solid var(--line);background:rgba(255,255,255,.03);color:var(--ink)}
.chips span:first-child{border-color:rgba(124,140,255,.4)}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
</style>
