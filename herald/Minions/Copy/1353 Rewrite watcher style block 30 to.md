# Copy: Rewrite watcher style block 30 to 40 lines no script

Date: 2026-11-01
Task: Rewrite Watcher style block, 30 to 40 lines, no script, must end with closing style tag
For [[Herald]].

<style>
:root{--ink:#e9ecf2;--mute:#9aa3b2;--pink:#ff2d8f;--cool:#2de2ff;--bg:#0b0d12;--line:rgba(255,255,255,.08);}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{min-height:100vh;color:var(--ink);background-color:var(--bg);font:16px/1.6 system-ui,-apple-system,"Segoe UI",sans-serif;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;background:radial-gradient(900px 600px at 15% 0%,rgba(45,226,255,.12),transparent 60%),radial-gradient(800px 600px at 90% 10%,rgba(255,45,143,.10),transparent 60%),radial-gradient(700px 500px at 50% 100%,rgba(45,226,255,.07),transparent 60%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:56px 56px,56px 56px;box-shadow:inset 0 0 160px 40px rgba(0,0,0,.6)}
.panel{position:relative;background:linear-gradient(180deg,rgba(255,255,255,.03),rgba(255,255,255,.01));border:1px solid var(--line);border-radius:14px;padding:clamp(16px,2.5vw,26px);max-width:1060px;margin:0 auto}
.panel h2{margin:0 0 8px;font-size:clamp(1.3rem,3vw,1.8rem);line-height:1.2}
.panel p{margin:0 0 12px;color:var(--mute);max-width:68ch}
.tag{display:inline-block;font-size:.72rem;letter-spacing:.14em;text-transform:uppercase;color:var(--cool);border:1px solid rgba(45,226,255,.4);padding:4px 10px;border-radius:999px;margin-bottom:12px}
.tag.hot{color:var(--pink);border-color:rgba(255,45,143,.45)}
.chip-row{display:grid;grid-template-columns:repeat(auto-fit,minmax(170px,1fr));gap:10px;margin:16px 0}
.chip{background:rgba(255,255,255,.025);border:1px solid var(--line);border-left:3px solid var(--cool);border-radius:10px;padding:12px 14px}
.chip:nth-child(2n){border-left-color:var(--pink)}
.chip-title{display:block;font-size:.78rem;letter-spacing:.08em;text-transform:uppercase;color:var(--mute);margin-bottom:4px}
.chip strong{font-size:1.05rem;color:var(--ink)}
.tablewrap{width:100%;overflow-x:auto;border:1px solid var(--line);border-radius:12px;margin:16px 0;-webkit-overflow-scrolling:touch}
.tablewrap table{width:100%;border-collapse:collapse;min-width:520px;font-size:.92rem}
.tablewrap th,.tablewrap td{text-align:left;padding:10px 12px;border-bottom:1px solid var(--line);white-space:nowrap}
.tablewrap th{color:var(--mute);font-weight:600;font-size:.76rem;letter-spacing:.08em;text-transform:uppercase}
.tablewrap td.up{color:var(--cool)}
.tablewrap td.dn{color:var(--pink)}
@media (max-width:700px){
.chip-row{grid-template-columns:1fr 1fr}
.panel{border-radius:12px}
}
@media (max-width:420px){
.chip-row{grid-template-columns:1fr}
}
.panel:focus-within{border-color:rgba(45,226,255,.25)}
::selection{background:var(--pink);color:#0b0d12}
a{color:var(--cool)}
</style>
