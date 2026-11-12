# Copy: Rewrite the crown style block accent must be ff2d8f six

Date: 2026-11-12
Task: Rewrite the Crown style block. Accent must be #ff2d8f (six hex digits). Add a fixed backdrop of two or three soft radial accent glows, a faint 56px grid at 1.5 
For [[Herald]].

```html
<style>
:root{--bg:#07070b;--ink:#e9e9f0;--muted:#9a9aab;--accent:#ff2d8f}
*{box-sizing:border-box;margin:0;padding:0}
html{background:var(--bg)}
body{position:relative;background:transparent;color:var(--ink);font:16px/1.6 system-ui,sans-serif;min-height:100vh}
/* fixed atmosphere: glows, faint grid, edge vignette. Static, no animation, no images */
body::before{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;
background:
radial-gradient(900px 600px at 12% -5%,rgba(255,45,143,.16),transparent 60%),
radial-gradient(760px 520px at 92% 18%,rgba(255,45,143,.10),transparent 62%),
radial-gradient(640px 460px at 40% 110%,rgba(255,45,143,.12),transparent 60%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;
background-image:
linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),
linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px),
radial-gradient(ellipse at center,transparent 45%,rgba(0,0,0,.65) 100%);
background-size:56px 56px,56px 56px,100% 100%}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
h1,h2{font-size:clamp(1.6rem,4vw,2.6rem);line-height:1.15}
p{max-width:65ch;color:var(--muted)}
.tag{color:var(--accent);font-size:.8rem;letter-spacing:.12em;text-transform:uppercase}
.chip{display:inline-block;border:1px solid var(--accent);padding:4px 10px;margin:4px}
.tablewrap{overflow-x:auto;width:100%}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:20px}
@media(max-width:700px){.grid{grid-template-columns:1fr}}
</style>
```
