# Copy: Write the css style block for the crown skeptic page

Date: 2026-10-30
Task: Write the CSS style block for the Crown skeptic page, under 40 lines.
For [[Herald]].

<style>
:root{--bg:#07070c;--ink:#e9e7f2;--mute:#9a97ab;--line:rgba(255,255,255,.08);--pink:#ff2d8f}
*{box-sizing:border-box}
html,body{margin:0;background:var(--bg);color:var(--ink);font:16px/1.6 system-ui,-apple-system,"Segoe UI",sans-serif}
body{position:relative;min-height:100vh;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background:radial-gradient(60vmax 45vmax at 12% -5%,rgba(255,45,143,.22),transparent 60%),radial-gradient(50vmax 40vmax at 92% 18%,rgba(255,45,143,.14),transparent 62%),radial-gradient(70vmax 50vmax at 50% 110%,rgba(255,45,143,.12),transparent 65%),var(--bg)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:56px 56px;box-shadow:inset 0 0 180px 60px rgba(0,0,0,.75)}
.bc-wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
.bc-head{padding:clamp(40px,8vw,88px) 0 clamp(24px,4vw,40px);border-bottom:1px solid var(--line)}
.bc-head h1{font-size:clamp(28px,5vw,52px);line-height:1.1;margin:0 0 .4em;letter-spacing:-.01em}
h2{font-size:clamp(20px,3vw,30px);margin:clamp(32px,5vw,56px) 0 .5em}
p,li{max-width:75ch}
.bc-head p{color:var(--mute);margin:0}
.panel{width:100%;margin:24px 0;padding:clamp(18px,3vw,28px);background:rgba(16,16,26,.72);border:1px solid var(--line);border-radius:14px;box-shadow:0 20px 60px -30px rgba(255,45,143,.25)}
.chips{display:flex;flex-wrap:wrap;gap:8px;list-style:none;padding:0;margin:16px 0}
.chips li,.chips span{max-width:none;padding:6px 12px;border:1px solid rgba(255,45,143,.35);border-radius:999px;font-size:13px}
.figure{width:100%;margin:28px 0;padding:clamp(14px,2.5vw,22px);border:1px solid var(--line);border-radius:12px;background:rgba(10,10,18,.8);overflow-x:auto}
.figure svg,.figure img{display:block;width:100%;height:auto}
.figure figcaption{color:var(--mute);font-size:13px;margin-top:10px}
.bc-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:16px}
@media (max-width:700px){.bc-grid{grid-template-columns:1fr}}
table{width:100%;border-collapse:collapse}
th,td{text-align:left;padding:10px 12px;border-bottom:1px solid var(--line)}
th{color:var(--pink)}
a{color:var(--pink)}
</style>
