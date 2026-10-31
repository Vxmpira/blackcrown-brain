# Copy: Write the watcher style block only a single style element

Date: 2026-10-31
Task: Write the Watcher style block only: a single style element, under 40 lines, no inline script, no fences, ending with the closing style tag.
For [[Herald]].

<style>
:root{--bg:#07080c;--ink:#e9ecf3;--mute:#8b93a7;--pink:#ff2d8f;--blue:#3aa0ff;--line:rgba(255,255,255,.08)}
*{box-sizing:border-box}
html,body{margin:0;background:var(--bg);color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif}
body{position:relative;min-height:100vh;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;background:radial-gradient(60vmax 45vmax at 12% 8%,rgba(255,45,143,.16),transparent 60%),radial-gradient(55vmax 45vmax at 90% 85%,rgba(58,160,255,.14),transparent 60%),var(--bg)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px),radial-gradient(ellipse at center,transparent 45%,rgba(0,0,0,.7) 100%);background-size:56px 56px,56px 56px,100% 100%}
.wt-wrap{max-width:1060px;margin:0 auto;padding:clamp(20px,4vw,48px) clamp(16px,4vw,32px)}
.wt-brand{display:flex;align-items:center;gap:12px;margin-bottom:clamp(24px,5vw,56px)}
.wt-brand svg{width:40px;height:40px;flex:none}
.wt-brand svg .acc{stroke:var(--pink)}
.wt-brand span{font-weight:700;letter-spacing:.08em;text-transform:uppercase;font-size:14px}
h1{font-size:clamp(30px,6vw,56px);line-height:1.08;margin:0 0 18px;letter-spacing:-.01em;max-width:18ch}
p{font-size:clamp(16px,2vw,18px);line-height:1.6;color:var(--ink);max-width:75ch;margin:0 0 16px}
.wt-chips{display:flex;flex-wrap:wrap;gap:10px;margin:24px 0 32px}
.wt-chips span{border:1px solid var(--line);background:rgba(255,255,255,.03);border-radius:999px;padding:7px 14px;font-size:14px;color:var(--ink)}
.wt-cta{display:flex;flex-wrap:wrap;align-items:center;gap:16px;margin-top:8px}
.wt-btn{display:inline-block;background:var(--pink);color:#fff;text-decoration:none;font-weight:700;padding:14px 26px;border-radius:10px;box-shadow:0 8px 28px rgba(255,45,143,.28)}
.wt-note{font-size:14px;color:var(--mute);max-width:60ch;margin:0}
.wt-disclaimer{font-size:12px;line-height:1.5;color:var(--mute);max-width:75ch;margin-top:40px;padding-top:18px;border-top:1px solid var(--line)}
@media (max-width:700px){.wt-cta{flex-direction:column;align-items:stretch}.wt-btn{text-align:center}.wt-chips span{font-size:13px}}
</style>
