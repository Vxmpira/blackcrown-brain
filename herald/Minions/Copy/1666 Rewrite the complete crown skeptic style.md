# Copy: Rewrite the complete crown skeptic style block closed with the

Date: 2026-11-13
Task: Rewrite the complete Crown skeptic style block, closed with the style tag, under 40 lines, pure CSS, no script.
For [[Herald]].

<style>
:root{--ink:#e9e6ef;--accent:#ff2d8f;--bg:#0c0b11;--mute:#a59fb3;--line:rgba(255,255,255,.08)}
*{box-sizing:border-box}
html,body{margin:0;background:var(--bg);color:var(--ink);font:17px/1.6 system-ui,-apple-system,"Segoe UI",Roboto,sans-serif}
body{position:relative;min-height:100vh;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background:radial-gradient(60vw 40vw at 15% 0%,rgba(255,45,143,.16),transparent 70%),radial-gradient(50vw 35vw at 90% 20%,rgba(255,45,143,.10),transparent 70%),linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:auto,auto,56px 56px,56px 56px}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.55) 100%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
h1{font-size:clamp(28px,5vw,52px);line-height:1.1;margin:.6em 0 .4em;letter-spacing:-.01em}
h2{font-size:clamp(22px,3.4vw,34px);line-height:1.2;margin:1.6em 0 .5em}
p{max-width:68ch;margin:0 0 1em;color:var(--ink)}
a{color:var(--accent)}
.tag{display:inline-block;font-size:12px;letter-spacing:.14em;text-transform:uppercase;color:var(--accent);border:1px solid rgba(255,45,143,.4);padding:4px 10px;border-radius:999px}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin:24px 0}
.card{border:1px solid var(--line);background:rgba(255,255,255,.02);border-radius:14px;padding:18px}
.tablewrap{width:100%;overflow-x:auto;margin:24px 0;border:1px solid var(--line);border-radius:12px}
.tablewrap table{width:100%;border-collapse:collapse;min-width:520px}
th,td{text-align:left;padding:12px 14px;border-bottom:1px solid var(--line)}
th{color:var(--mute);font-weight:600;font-size:13px}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
</style>
