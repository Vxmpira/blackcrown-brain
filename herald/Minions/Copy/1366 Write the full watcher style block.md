# Copy: Write the full watcher style block opening style tag through

Date: 2026-11-01
Task: Write the full Watcher style block, opening style tag through closing style tag.
For [[Herald]].

<style>
:root{--ink:#07080c;--pink:#ff2d8f;--cool:#3ad1ff;--text:#e8eaf0;--muted:#9aa1b2;--line:rgba(255,255,255,.08)}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{background-color:var(--ink);color:var(--text);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6;min-height:100vh;background-image:radial-gradient(60% 40% at 15% 0%,rgba(255,45,143,.14),transparent 70%),radial-gradient(50% 40% at 90% 10%,rgba(58,209,255,.10),transparent 70%),linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:auto,auto,56px 56px,56px 56px;background-attachment:fixed}
body::after{content:"";position:fixed;inset:0;pointer-events:none;background:radial-gradient(120% 90% at 50% 50%,transparent 55%,rgba(0,0,0,.55) 100%);z-index:0}
.wrap{position:relative;z-index:1;max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
h1,h2,h3{line-height:1.15;margin:0 0 .5em;font-weight:700;letter-spacing:-.01em}
h1{font-size:clamp(1.9rem,5vw,3.2rem)}
h2{font-size:clamp(1.4rem,3.4vw,2.1rem)}
h3{font-size:clamp(1.05rem,2.4vw,1.3rem)}
p,ul,ol{max-width:75ch;margin:0 0 1em}
a{color:var(--cool)}
.logo{display:inline-flex;align-items:center;width:clamp(36px,6vw,48px);height:auto}
.logo svg{display:block;width:100%;height:auto}
.grid{display:grid;gap:clamp(12px,2.4vw,20px);grid-template-columns:repeat(3,minmax(0,1fr))}
.card{border:1px solid var(--line);background:rgba(10,12,18,.72);border-radius:14px;padding:clamp(16px,2.6vw,24px)}
.chip{display:inline-block;padding:.3em .75em;margin:0 .4em .4em 0;border:1px solid rgba(255,45,143,.45);border-radius:999px;font-size:.82rem;color:var(--text);background:rgba(255,45,143,.08)}
.chip.cool{border-color:rgba(58,209,255,.45);background:rgba(58,209,255,.08)}
.tablewrap{width:100%;overflow-x:auto;-webkit-overflow-scrolling:touch;border:1px solid var(--line);border-radius:12px;margin:0 0 1.5em}
.tablewrap table{width:100%;border-collapse:collapse;min-width:520px;font-size:.95rem}
.tablewrap th,.tablewrap td{padding:.7em .9em;text-align:left;border-bottom:1px solid var(--line);white-space:nowrap}
.tablewrap th{color:var(--muted);font-weight:600;font-size:.8rem;text-transform:uppercase;letter-spacing:.06em}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
</style>
