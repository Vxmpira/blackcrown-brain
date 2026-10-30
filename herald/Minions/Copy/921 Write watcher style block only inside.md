# Copy: Write watcher style block only inside a style tag under

Date: 2026-10-30
Task: Write Watcher style block only, inside a style tag, under 40 lines, no script, closing style tag last.
For [[Herald]].

<style>
:root{--bg:#07080c;--panel:#0d0f16;--line:rgba(255,255,255,.08);--ink:#e8ecf3;--muted:#9aa4b5;--accent:#7c5cff;--gold:#e0b04a;--green:#3ddc97;--red:#ff6b6b}
*{box-sizing:border-box}
html{-webkit-text-size-adjust:100%}
body{margin:0;min-height:100vh;color:var(--ink);font:16px/1.6 system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;background:radial-gradient(900px 500px at 12% -10%,rgba(124,92,255,.22),transparent 60%),radial-gradient(700px 420px at 92% 8%,rgba(224,176,74,.10),transparent 60%),linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px),var(--bg);background-size:auto,auto,56px 56px,56px 56px,auto;background-attachment:fixed}
body::after{content:"";position:fixed;inset:0;pointer-events:none;background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.55) 100%)}
.wrap,header,main{width:min(1060px,calc(100% - 32px));margin-inline:auto}
header{display:flex;align-items:center;justify-content:space-between;gap:16px;padding:22px 0;border-bottom:1px solid var(--line)}
h1{margin:28px 0 10px;font-size:clamp(1.6rem,4.2vw,2.6rem);line-height:1.15;letter-spacing:-.01em;font-weight:700}
h2{margin:0 0 8px;font-size:clamp(1.1rem,2.4vw,1.4rem);font-weight:650}
small{display:block;color:var(--muted);font-size:.85rem;letter-spacing:.02em}
.panel{background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:clamp(16px,2.5vw,24px);margin:18px 0;box-shadow:0 0 0 1px rgba(124,92,255,.06) inset}
figure{margin:20px 0;display:grid;grid-template-columns:repeat(3,1fr);gap:12px;border:1px solid var(--line);border-radius:14px;background:var(--panel);padding:16px;position:relative}
figure span{display:flex;flex-direction:column;justify-content:center;min-height:84px;padding:12px;border-radius:10px;border:1px solid var(--line);background:rgba(255,255,255,.02);color:var(--muted);font-size:.9rem}
figure span:nth-child(1){border-color:rgba(61,220,151,.35);color:var(--green)}
figure span:nth-child(2){border-color:rgba(224,176,74,.35);color:var(--gold)}
figure span:nth-child(3){border-color:rgba(255,107,107,.35);color:var(--red)}
a{color:var(--accent);text-decoration:none;border-bottom:1px solid rgba(124,92,255,.35)}
a:hover{color:var(--ink);border-bottom-color:var(--ink)}
@media (max-width:700px){figure{grid-template-columns:1fr}header{flex-direction:column;align-items:flex-start}figure span{min-height:64px}}
</style>
