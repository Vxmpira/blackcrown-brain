# Copy: Write watcher style block css only under 40 lines no

Date: 2026-10-31
Task: Write Watcher style block: CSS only, under 40 lines, no script, ending in closing style tag.
For [[Herald]].

<style>
:root{--bg:#07070b;--ink:#eceaf2;--mute:#9a97a8;--pink:#ff2d8f;--gold:#e8c35a;--line:rgba(255,255,255,.08)}
*{box-sizing:border-box}
html,body{margin:0;padding:0;background:var(--bg);color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6;-webkit-font-smoothing:antialiased}
body{position:relative;min-height:100vh;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background:radial-gradient(900px 600px at 12% -10%,rgba(255,45,143,.16),transparent 60%),radial-gradient(800px 560px at 96% 8%,rgba(232,195,90,.10),transparent 60%),radial-gradient(700px 500px at 50% 110%,rgba(255,45,143,.09),transparent 60%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:56px 56px;-webkit-mask-image:radial-gradient(ellipse at center,#000 40%,transparent 85%);mask-image:radial-gradient(ellipse at center,#000 40%,transparent 85%)}
.vignette{position:fixed;inset:0;z-index:-1;pointer-events:none;background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.65) 100%)}
.container{width:min(1060px,calc(100% - 2rem));margin:0 auto}
h1,h2,h3{line-height:1.15;letter-spacing:-.01em;margin:0 0 .6em;font-weight:700}
h1{font-size:clamp(2rem,5vw,3.4rem)}
h2{font-size:clamp(1.4rem,3vw,2rem)}
h3{font-size:clamp(1.1rem,2.2vw,1.3rem)}
p,li{max-width:75ch}
p{margin:0 0 1em;color:var(--ink)}
a{color:var(--gold);text-decoration:none}
a:hover{color:var(--pink)}
.hero{padding:clamp(3rem,8vw,6rem) 0 clamp(2rem,5vw,3.5rem);border-bottom:1px solid var(--line)}
.hero p{color:var(--mute);font-size:clamp(1rem,1.8vw,1.15rem)}
.chips{display:flex;flex-wrap:wrap;gap:.6rem;margin:1.5rem 0 0;padding:0;list-style:none}
.chips li{border:1px solid rgba(255,45,143,.45);background:rgba(255,45,143,.08);color:var(--ink);border-radius:999px;padding:.35rem .9rem;font-size:.85rem;max-width:none}
.chips li:nth-child(even){border-color:rgba(232,195,90,.45);background:rgba(232,195,90,.07)}
.tablewrap{width:100%;overflow-x:auto;border:1px solid var(--line);border-radius:12px;background:rgba(255,255,255,.02);margin:1.5rem 0}
.tablewrap table{width:100%;border-collapse:collapse;min-width:520px}
.tablewrap th,.tablewrap td{padding:.75rem 1rem;text-align:left;border-bottom:1px solid var(--line);font-size:.95rem}
.tablewrap th{color:var(--gold);font-weight:600}
@media (max-width:700px){.grid{grid-template-columns:1fr!important}.hero{text-align:left}}
</style>
