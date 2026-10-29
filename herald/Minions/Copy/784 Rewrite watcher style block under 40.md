# Copy: Rewrite watcher style block under 40 lines closing style tag

Date: 2026-10-29
Task: Rewrite Watcher style block, under 40 lines, closing style tag last.
For [[Herald]].

```html
<style>
:root{--ink:#07070b;--pink:#ff2d8f;--mute:#9a94a6;--line:rgba(255,255,255,.08)}
*{box-sizing:border-box}
html{background:var(--ink)}
body{
  margin:0;min-height:100vh;color:#ece9f2;
  font:16px/1.6 system-ui,-apple-system,"Segoe UI",sans-serif;
  background:
    radial-gradient(900px 600px at 85% -10%,rgba(255,45,143,.16),transparent 60%),
    radial-gradient(700px 500px at -10% 110%,rgba(255,45,143,.10),transparent 60%),
    linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),
    linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px),
    var(--ink);
  background-size:auto,auto,56px 56px,56px 56px;
}
body::after{
  content:"";position:fixed;inset:0;pointer-events:none;
  background:radial-gradient(120% 90% at 50% 50%,transparent 55%,rgba(0,0,0,.55) 100%);
}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
h1{font-size:clamp(2rem,4.2vw,3.4rem);line-height:1.1;margin:0 0 .5em;letter-spacing:-.02em}
h2{font-size:clamp(1.4rem,2.6vw,2rem);margin:1.6em 0 .5em}
p,li{max-width:75ch}
.mute{color:var(--mute)}
.accent{color:var(--pink)}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
.chip{border:1px solid var(--line);border-radius:999px;padding:6px 12px;color:var(--mute);font-size:14px}
table,.figure{width:100%}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
</style>
```

The closing `</style>` tag is present and is the last line of the block. The block runs 31 lines and uses only the ink, pink, and mute palette, with no animation, images, or script.
