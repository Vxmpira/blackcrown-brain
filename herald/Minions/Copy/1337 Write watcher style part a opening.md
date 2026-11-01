# Copy: Write watcher style part a opening style tag html and

Date: 2026-11-01
Task: Write Watcher style part A: opening style tag, html and body reset, body text color and font, and the fixed body::before backdrop with three radial glows and th
For [[Herald]].

```html
<style>
*,*::before,*::after{box-sizing:border-box}
html,body{margin:0;padding:0}
html{background:#080810;color-scheme:dark;-webkit-text-size-adjust:100%}
body{background:transparent;color:#e9e9f1;font-family:system-ui,-apple-system,"Segoe UI",sans-serif;font-size:16px;line-height:1.6;min-height:100vh;overflow-x:hidden;-webkit-font-smoothing:antialiased}
body::before{
  content:"";
  position:fixed;
  inset:0;
  z-index:-2;
  pointer-events:none;
  background:
    radial-gradient(60% 50% at 85% 0%,rgba(255,45,143,.16),transparent 70%),
    radial-gradient(55% 45% at 0% 35%,rgba(120,80,255,.12),transparent 70%),
    radial-gradient(50% 40% at 60% 100%,rgba(255,45,143,.08),transparent 70%),
    repeating-linear-gradient(0deg,rgba(255,255,255,.015) 0 1px,transparent 1px 56px),
    repeating-linear-gradient(90deg,rgba(255,255,255,.015) 0 1px,transparent 1px 56px);
}
/* end part A: continue with part B */
```
