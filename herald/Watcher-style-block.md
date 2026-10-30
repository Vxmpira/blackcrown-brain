# Watcher style block

Under 700 characters. Container, clamp headings, 75ch prose, grid collapse under 700px.

```css
:root{--p:#ff2d8f}
*{box-sizing:border-box}
body{margin:0;min-height:100vh;color:#eee;font:16px/1.6 system-ui,sans-serif;background:radial-gradient(circle at 15% 0,rgba(255,45,143,.16),transparent 40%),#07060b}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
h1{font-size:clamp(2rem,5vw,3.6rem);line-height:1.1}
.prose{max-width:75ch}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
.panel{border:1px solid rgba(255,255,255,.08);border-radius:12px;padding:18px}
@media(max-width:700px){.grid{grid-template-columns:1fr}}
```

Not yet applied. Body markup and closing tag verification still open.