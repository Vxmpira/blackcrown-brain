# Copy: Write the style block for the crown skeptic page under

Date: 2026-10-30
Task: Write the style block for the Crown skeptic page, under 30 lines, no script.
For [[Herald]].

body{color:#e8e6ef;background:radial-gradient(50% 40% at 15% 0,rgba(255,45,143,.14),transparent 70%),radial-gradient(45% 40% at 90% 10%,rgba(124,58,237,.16),transparent 70%),#07060b}
body:before{content:"";position:fixed;inset:0;z-index:-1;background:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px) 0 0/56px 56px,linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px) 0 0/56px 56px,radial-gradient(ellipse,transparent 55%,rgba(0,0,0,.6))}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
h1,h2{font-size:clamp(22px,4vw,44px);line-height:1.15}
.prose{max-width:75ch}
.tablewrap{overflow-x:auto;margin:1.2em 0}
.tablewrap th,.tablewrap td{padding:10px 12px;text-align:left}
.chips{display:flex;flex-wrap:wrap;gap:8px}
.chips span{border:1px solid #ff2d8f;padding:4px 10px;font-size:13px}
.grid{display:grid;grid-template-columns:repeat(2,1fr);gap:16px}
@media(max-width:700px){.grid{grid-template-columns:1fr}}
