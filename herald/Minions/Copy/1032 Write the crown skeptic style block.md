# Copy: Write the crown skeptic style block css only under 40

Date: 2026-10-30
Task: Write the Crown skeptic style block, CSS only, under 40 lines.
For [[Herald]].

<style>
:root{--pink:#ff2d8f;--violet:#7a5cff;--ink:#e9e6f2;--mute:#a9a3ba}
html,body{margin:0;background:#0b0710;color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",sans-serif;line-height:1.6}
body{position:relative;min-height:100vh;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;background:radial-gradient(60vw 45vh at 85% 0%,rgba(255,45,143,.16),transparent 70%),radial-gradient(55vw 50vh at 0% 100%,rgba(122,92,255,.10),transparent 70%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:56px 56px;box-shadow:inset 0 0 160px 40px rgba(0,0,0,.6)}
section{display:grid;grid-template-columns:minmax(0,1fr);gap:0 24px;max-width:1060px;margin:0 auto;padding:48px 20px}
@media (min-width:700px){section{grid-template-columns:1fr 1fr;column-gap:40px;padding:72px 28px}}
h1{grid-column:1/-1;font-size:clamp(32px,5vw,56px);line-height:1.1;letter-spacing:-.02em;margin:0 0 16px}
h2{grid-column:1/-1;font-size:clamp(22px,3vw,32px);line-height:1.2;margin:24px 0 12px}
p{margin:0 0 16px}
.crown-head{grid-column:1/-1;font-size:clamp(13px,1.3vw,15px);text-transform:uppercase;letter-spacing:.18em;color:var(--pink);font-weight:600;margin:0 0 12px}
.crown-body-1{font-size:clamp(16px,1.5vw,18px);max-width:75ch;color:#d9d4e6;margin:0 0 16px}
.crown-body-2{font-size:15px;max-width:75ch;color:var(--mute);margin:0 0 16px}
.chip{display:inline-block;padding:6px 12px;margin:0 8px 8px 0;border:1px solid rgba(255,45,143,.35);border-radius:999px;font-size:13px;background:rgba(255,255,255,.03)}
.crown-cta{display:inline-block;padding:12px 22px;background:var(--pink);color:#0b0710;font-weight:700;text-decoration:none;border-radius:6px;box-shadow:0 0 24px rgba(255,45,143,.35)}
a{color:#ff7ab8}
@media (max-width:699px){.chip{margin-right:6px}}
</style>

Closing style tag confirmed: </style> is the final line of this block.
