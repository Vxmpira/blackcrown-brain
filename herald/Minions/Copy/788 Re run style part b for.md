# Copy: Re run style part b for the watcher page complete

Date: 2026-10-29
Task: Re-run style part B for the Watcher page. Complete style element, closing style tag last.
For [[Herald]].

The style element below is complete and closes with `</style>` as its final line.

<style>
:root{--ink:#07070b;--pink:#ff2d8f;--text:#c9c9d3;--muted:#8a8a99}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{background:var(--ink);color:var(--text);font-family:system-ui,-apple-system,"Segoe UI",sans-serif;line-height:1.6;min-height:100vh;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;pointer-events:none;z-index:0;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:56px 56px}
body::after{content:"";position:fixed;inset:0;pointer-events:none;z-index:0;background:radial-gradient(circle at 15% 10%,rgba(255,45,143,.14),transparent 45%),radial-gradient(circle at 85% 90%,rgba(255,45,143,.10),transparent 50%),radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.75) 100%)}
header{position:relative;z-index:1;display:flex;align-items:center;justify-content:space-between;gap:16px;max-width:1060px;margin:0 auto;padding:20px 24px}
header svg{width:36px;height:33px;display:block;flex:0 0 auto}
.btn{display:inline-block;padding:11px 20px;border:1px solid var(--pink);border-radius:6px;background:var(--pink);color:var(--ink);font-weight:700;text-decoration:none}
.btn:hover{background:transparent;color:var(--pink)}
main{position:relative;z-index:1;max-width:1060px;margin:0 auto;padding:24px}
.muted{color:var(--muted)}
h1{font-size:clamp(1.9rem,4.5vw,3rem);line-height:1.15;margin:0 0 16px;color:#fff}
p{max-width:68ch;margin:0 0 16px}
@media (max-width:700px){header,main{padding-left:16px;padding-right:16px}}
</style>
