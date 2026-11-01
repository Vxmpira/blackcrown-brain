# Copy: Write watcher style block under 40 lines no script closing

Date: 2026-11-01
Task: Write Watcher style block under 40 lines, no script, closing tag required
For [[Herald]].

<style>
:root{--ink:#e9ecf2;--mute:#9aa3b2;--pink:#ff2d8f;--cool:#2de2ff;--bg:#0b0d12;--line:rgba(255,255,255,.08)}
*{box-sizing:border-box}
html,body{margin:0;background:var(--bg);color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",sans-serif;line-height:1.6}
body{position:relative;min-height:100vh;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;background:radial-gradient(900px 600px at 15% 0%,rgba(255,45,143,.22),transparent 60%),radial-gradient(800px 560px at 90% 10%,rgba(45,226,255,.14),transparent 60%),radial-gradient(700px 500px at 50% 100%,rgba(255,45,143,.10),transparent 65%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px),radial-gradient(ellipse at center,transparent 45%,rgba(0,0,0,.65) 100%);background-size:56px 56px,56px 56px,100% 100%}
.container{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
.hero{padding:clamp(48px,9vw,96px) 0 clamp(24px,4vw,40px)}
.brand{font-size:.8rem;letter-spacing:.18em;text-transform:uppercase;color:var(--cool);margin:0 0 12px}
.hero h1{font-size:clamp(2rem,5.5vw,3.6rem);line-height:1.1;margin:0 0 16px;font-weight:700}
.sub{font-size:clamp(1rem,2vw,1.15rem);color:var(--mute);max-width:75ch;margin:0 0 24px}
.btn{display:inline-block;padding:12px 22px;border-radius:10px;background:var(--pink);color:#fff;text-decoration:none;font-weight:600}
.note{font-size:.85rem;color:var(--mute);max-width:75ch;margin:12px 0 0}
.panel{background:rgba(255,255,255,.03);border:1px solid var(--line);border-radius:14px;padding:clamp(18px,3vw,28px);margin:28px 0}
.tag{display:inline-block;font-size:.72rem;padding:4px 10px;border-radius:999px;border:1px solid rgba(255,45,143,.5);color:var(--pink);margin-right:6px}
.chip-row{display:grid;grid-template-columns:repeat(3,1fr);gap:14px;margin:24px 0}
.chip{border:1px solid var(--line);border-radius:12px;padding:14px 16px;background:rgba(255,255,255,.025)}
.chip-title{font-weight:600;margin:0 0 4px;color:var(--ink)}
.tablewrap{width:100%;overflow-x:auto;border:1px solid var(--line);border-radius:12px;margin:24px 0}
.tablewrap table{width:100%;border-collapse:collapse}
.tablewrap th,.tablewrap td{padding:10px 14px;text-align:left;border-bottom:1px solid var(--line)}
.cta{text-align:center;padding:clamp(32px,6vw,56px) 0}
.footer{font-size:.8rem;color:var(--mute);border-top:1px solid var(--line);padding:24px 0;margin-top:40px}
@media (max-width:699px){.chip-row{grid-template-columns:1fr}.hero h1{font-size:clamp(1.8rem,8vw,2.2rem)}}
</style>
