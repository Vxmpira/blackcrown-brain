# Copy: Write crown skeptic style block style to style under 40

Date: 2026-11-12
Task: Write Crown skeptic style block: <style> to </style>, under 40 lines, no inline script.
For [[Herald]].

<style>
:root{--bg:#07070b;--ink:#e9e9f0;--mute:#9a9aab;--pink:#ff2d8f}
*{box-sizing:border-box}
html,body{margin:0;min-height:100%}
body{background:var(--bg);color:var(--ink);font:16px/1.6 system-ui,-apple-system,"Segoe UI",sans-serif;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background:radial-gradient(900px 520px at 12% -6%,rgba(255,45,143,.14),transparent 70%),radial-gradient(820px 480px at 92% 8%,rgba(90,120,255,.10),transparent 70%),radial-gradient(760px 420px at 50% 112%,rgba(255,45,143,.07),transparent 70%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px),radial-gradient(ellipse at center,transparent 45%,rgba(0,0,0,.65) 100%);background-size:56px 56px,56px 56px,100% 100%}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
h1{font-size:clamp(28px,5vw,46px);line-height:1.15;margin:0 0 .5em;letter-spacing:-.01em}
h2{font-size:clamp(20px,3.2vw,28px);line-height:1.25;margin:1.6em 0 .5em}
p,ul{max-width:75ch}
.mute{color:var(--mute)}
.accent{color:var(--pink)}
.skeptic{border-left:3px solid var(--pink);padding:12px 18px;margin:1.2em 0;background:rgba(255,255,255,.02);max-width:75ch}
.tablewrap{width:100%;overflow-x:auto;border:1px solid rgba(255,255,255,.08);border-radius:10px;margin:1.2em 0}
table{width:100%;border-collapse:collapse;min-width:520px}
th,td{padding:10px 14px;text-align:left;border-bottom:1px solid rgba(255,255,255,.06)}
th{color:var(--mute);font-weight:600}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
.card{border:1px solid rgba(255,255,255,.08);border-radius:12px;padding:18px;background:rgba(255,255,255,.02)}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
</style>
