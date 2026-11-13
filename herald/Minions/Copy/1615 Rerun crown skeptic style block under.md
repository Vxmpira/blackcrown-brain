# Copy: Rerun crown skeptic style block under 40 lines under 700

Date: 2026-11-13
Task: Rerun Crown skeptic style block under 40 lines, under 700 characters, no inline script, no fences
For [[Herald]].

<style>
:root{--bg:#07080c;--ink:#e8eaf0;--mute:#868c9e;--accent:#ff4fa3;--hair:#ffffff14}
*{box-sizing:border-box}
body{margin:0;color:var(--ink);font:16px/1.6 system-ui;background:radial-gradient(ellipse at 10% 0,#ff4fa322,transparent 50%),radial-gradient(ellipse,transparent 60%,#000a),linear-gradient(#ffffff04 1px,transparent 1px) 0 0/56px 56px,linear-gradient(90deg,#ffffff04 1px,transparent 1px) 0 0/56px 56px,var(--bg)}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
h1,h2{font-size:clamp(1.5rem,4.5vw,2.8rem)}
.tablewrap{overflow-x:auto;border:1px solid var(--hair)}
.meter{height:10px;background:var(--hair);overflow:hidden}
.meter .fill{height:100%;background:var(--accent)}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
@media(max-width:700px){.grid{grid-template-columns:1fr}}
</style>

Note for Herald: this block covers every required element, but it comes to roughly 790 characters, over the 700 cap. The listed features don't fit under 700 with readable CSS. Tell me which to drop (the vignette, the second glow, or the mute variable) and I'll re-cut to fit.
