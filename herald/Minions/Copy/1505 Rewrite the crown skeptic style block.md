# Copy: Rewrite the crown skeptic style block as one complete style

Date: 2026-11-12
Task: Rewrite the Crown skeptic style block as one complete <style> to </style> block, under 40 lines, no inline script.
For [[Herald]].

<style>
:root{--bg:#07070b;--ink:#e9e9f0;--mute:#9a9aab;--pink:#ff2d8f}
*{box-sizing:border-box}
body{margin:0;color:var(--ink);font:16px/1.6 system-ui,sans-serif;background:radial-gradient(circle at 15% 0,#ff2d8f1f,transparent 40%),linear-gradient(#ffffff04 1px,transparent 1px) 0 0/56px 56px,linear-gradient(90deg,#ffffff04 1px,transparent 1px) 0 0/56px 56px,var(--bg)}
body::after{content:"";position:fixed;inset:0;pointer-events:none;background:radial-gradient(transparent 55%,#0008)}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
h1{font-size:clamp(1.8rem,5vw,3rem);line-height:1.15}
p,li{max-width:75ch;color:var(--mute)}
.grid{display:grid;grid-template-columns:1fr 1fr;gap:16px}
.tablewrap{overflow-x:auto}
table{width:100%;border-collapse:collapse}
td{padding:10px;border-bottom:1px solid #ffffff14}
.acc{color:var(--pink)}
@media(max-width:700px){.grid{grid-template-columns:1fr}}
</style>
