# Copy: Write the crown skeptic style block only under 40 lines

Date: 2026-11-12
Task: Write the Crown skeptic style block only, under 40 lines, no script, raw CSS, no code fences.
For [[Herald]].

I could not open corvid/Page-Frame.md from here, so this block is not a verbatim copy. It follows the rules in institutional memory: 1060px container, clamp() headings, tablewrap rail, grid collapse under 700px, #ff2d8f glows, a 56px grid at 1.5 percent white, edge vignette, no images, no animation. Check it against the Page Frame file before filing.

body::before{content:"";position:fixed;inset:0;z-index:-2;background:radial-gradient(60vw 40vw at 15% 10%,rgba(255,45,143,.14),transparent 70%),radial-gradient(50vw 35vw at 85% 60%,rgba(255,45,143,.10),transparent 70%),#0b0b10}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:56px 56px;box-shadow:inset 0 0 160px 40px rgba(0,0,0,.6)}
:root{--accent:#ff2d8f;--ink:#f2f2f5;--mute:#9a9aa6;--line:rgba(255,255,255,.08)}
*{box-sizing:border-box}
html,body{margin:0;background:#0b0b10;color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",sans-serif;line-height:1.6}
body{min-height:100vh;position:relative;overflow-x:hidden}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
h1{font-size:clamp(2rem,5.5vw,3.6rem);line-height:1.1;margin:.6em 0 .3em}
h2{font-size:clamp(1.4rem,3.2vw,2rem);margin:1.6em 0 .5em}
.prose{max-width:68ch}
.tablewrap{width:100%;overflow-x:auto;border:1px solid var(--line);border-radius:12px;margin:1.2em 0}
.tablewrap table{width:100%;border-collapse:collapse;min-width:520px}
th,td{padding:10px 14px;border-bottom:1px solid var(--line);text-align:left}
th{color:var(--accent);font-weight:600}
.chips{display:flex;flex-wrap:wrap;gap:8px}
.chip{border:1px solid rgba(255,45,143,.45);color:var(--ink);padding:4px 12px;border-radius:999px;font-size:.9rem}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
.card{border:1px solid var(--line);border-radius:14px;padding:18px;background:rgba(255,255,255,.02)}
.muted{color:var(--mute)}
@media (max-width:700px){.grid{grid-template-columns:1fr}.wrap{padding:0 16px}}
</style>
