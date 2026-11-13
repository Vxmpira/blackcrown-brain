# Copy: Write crown skeptic style block under 40 lines pure css

Date: 2026-11-13
Task: Write Crown skeptic style block, under 40 lines, pure CSS
For [[Herald]].

<style>
:root{--ink:#e9e6ef;--mute:#9a95a8;--accent:#ff2d8f;--line:rgba(255,255,255,.08)}
*{box-sizing:border-box}
html{background:#0c0b11;color:var(--ink);font:16px/1.6 system-ui,-apple-system,"Segoe UI",sans-serif}
body{margin:0;position:relative;z-index:0;min-height:100vh;overflow-x:hidden}
/* fixed backdrop: accent glows, faint 56px grid, edge vignette. No images, no motion */
body::before{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;
background:
radial-gradient(60vmax 40vmax at 12% 8%,rgba(255,45,143,.16),transparent 70%),
radial-gradient(50vmax 36vmax at 90% 35%,rgba(255,45,143,.10),transparent 70%),
radial-gradient(70vmax 45vmax at 50% 105%,rgba(255,45,143,.12),transparent 70%),
linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),
linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px),
radial-gradient(120% 90% at 50% 50%,transparent 55%,rgba(0,0,0,.55) 100%);
background-size:auto,auto,auto,56px 56px,56px 56px,auto}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
h1{font-size:clamp(28px,5vw,52px);line-height:1.1;letter-spacing:-.01em;margin:.6em 0 .4em}
h2{font-size:clamp(22px,3.4vw,34px);line-height:1.2;margin:1.6em 0 .5em}
.prose{max-width:75ch}
.prose p{margin:0 0 1em}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:16px 0}
.chip{border:1px solid rgba(255,45,143,.45);background:rgba(255,45,143,.08);border-radius:999px;padding:6px 12px;font-size:14px}
.grid{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:16px}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
.tablewrap{width:100%;overflow-x:auto;-webkit-overflow-scrolling:touch;border:1px solid var(--line);border-radius:10px}
.tablewrap table{width:100%;min-width:520px;border-collapse:collapse}
.tablewrap th,.tablewrap td{padding:10px 12px;text-align:left;font-size:15px;border-bottom:1px solid var(--line)}
.tablewrap th{color:var(--mute);font-weight:600}
a{color:var(--accent)}
</style>
