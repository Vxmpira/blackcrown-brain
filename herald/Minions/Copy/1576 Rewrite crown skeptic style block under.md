# Copy: Rewrite crown skeptic style block under 40 lines no script

Date: 2026-11-13
Task: Rewrite Crown skeptic style block, under 40 lines, no script, closed with </style>
For [[Herald]].

<style>
:root{--pink:#ff2d8f;--violet:#7b5cff;--ink:#e9e7ee;--mute:#9a97a6;--bg:#0c0b12}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{
  color:var(--ink);
  font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;
  line-height:1.6;
  min-height:100vh;
  background-color:#14121d;
  background-image:
    radial-gradient(60% 40% at 15% 0%,rgba(255,45,143,.10),transparent 70%),
    radial-gradient(50% 35% at 90% 10%,rgba(123,92,255,.10),transparent 70%),
    linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),
    linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px),
    radial-gradient(120% 90% at 50% 50%,transparent 55%,rgba(0,0,0,.55) 100%);
  background-size:auto,auto,56px 56px,56px 56px,auto;
  background-attachment:fixed;
}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
h1,h2,h3{margin:0 0 .5em;line-height:1.15}
h1{font-size:clamp(1.8rem,4.5vw,3rem)}
h2{font-size:clamp(1.3rem,3vw,1.9rem)}
h3{font-size:clamp(1.05rem,2.2vw,1.25rem)}
p{margin:0 0 1em;max-width:68ch;color:var(--ink)}
.mute{color:var(--mute)}
.accent{color:var(--pink)}
.grid{display:grid;gap:clamp(12px,2vw,20px);grid-template-columns:repeat(3,1fr)}
.card{border:1px solid rgba(255,255,255,.08);border-radius:14px;padding:clamp(16px,2.5vw,24px);background:rgba(12,11,18,.6)}
.chip{display:inline-block;font-size:.8rem;padding:4px 10px;border-radius:999px;border:1px solid rgba(255,45,143,.4);color:var(--pink);margin:0 6px 6px 0}
.tablewrap{width:100%;overflow-x:auto;border:1px solid rgba(255,255,255,.08);border-radius:12px}
table{width:100%;border-collapse:collapse}
th,td{text-align:left;padding:10px 14px;border-bottom:1px solid rgba(255,255,255,.06)}
@media (max-width:700px){
  .grid{grid-template-columns:1fr}
  .wrap{padding:0 16px}
}
</style>
