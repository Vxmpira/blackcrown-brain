# Copy: Rerun watcher page style block complete under 40 lines ends

Date: 2026-11-13
Task: Rerun Watcher page style block, complete, under 40 lines, ends with closing style tag
For [[Herald]].

<style>
:root{--accent:#ff2d8f;--ink:#e9e9ef;--muted:#9a9aa8;--ground:#0b0b11;--line:#1f1f2a}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",Roboto,Helvetica,Arial,sans-serif;line-height:1.6;min-height:100vh;position:relative;overflow-x:hidden;background:radial-gradient(60% 40% at 15% 0%,rgba(255,45,143,.14),transparent 70%),radial-gradient(50% 35% at 90% 10%,rgba(255,45,143,.08),transparent 70%),var(--ground)}
body::before{content:"";position:fixed;inset:0;pointer-events:none;z-index:0;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:56px 56px}
body::after{content:"";position:fixed;inset:0;pointer-events:none;z-index:0;background:radial-gradient(120% 90% at 50% 50%,transparent 55%,rgba(0,0,0,.55) 100%)}
.wrap{position:relative;z-index:1;max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
h1{font-size:clamp(28px,5vw,52px);line-height:1.1;margin:0 0 .5em;letter-spacing:-.01em}
h2{font-size:clamp(20px,3vw,28px);line-height:1.2;margin:1.6em 0 .5em}
p{max-width:68ch;margin:0 0 1em}
.muted{color:var(--muted)}
.accent{color:var(--accent)}
.grid{display:grid;gap:16px;grid-template-columns:repeat(3,1fr)}
.card{border:1px solid var(--line);border-radius:12px;padding:18px;background:rgba(18,18,26,.6)}
.chip{display:inline-block;font-size:13px;padding:4px 10px;border-radius:999px;border:1px solid var(--accent);color:var(--accent);margin:0 6px 6px 0}
.tablewrap{width:100%;overflow-x:auto;border:1px solid var(--line);border-radius:12px}
table{width:100%;border-collapse:collapse}
th,td{padding:10px 12px;text-align:left;border-bottom:1px solid var(--line)}
th{color:var(--muted);font-weight:600}
figure{margin:24px 0;width:100%}
svg{display:block;max-width:100%;height:auto}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
</style>
