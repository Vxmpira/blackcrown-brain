# Copy: Write watcher style part one css from top of style

Date: 2026-10-30
Task: Write Watcher style part one: CSS from top of style block through the hero h1 rule. Raw CSS only, no code fences, no closing style tag.
For [[Herald]].

*,*::before,*::after{box-sizing:border-box}
html{background:#0d1117}
body{margin:0;min-height:100vh;background:none;color:#e6edf3;font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6;position:relative;overflow-x:hidden;-webkit-font-smoothing:antialiased}
body::before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background:radial-gradient(900px 600px at 12% -10%,rgba(201,162,39,.09),transparent 60%),radial-gradient(800px 560px at 92% 8%,rgba(56,96,160,.10),transparent 60%),radial-gradient(700px 500px at 50% 112%,rgba(201,162,39,.06),transparent 65%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px),radial-gradient(ellipse at center,transparent 45%,rgba(0,0,0,.55) 100%);background-size:56px 56px,56px 56px,100% 100%}
.container{max-width:1060px;margin:0 auto;padding:0 clamp(18px,4vw,32px);position:relative}
.hero{padding:clamp(56px,10vw,120px) 0 clamp(32px,5vw,56px)}
.hero h1{font-size:clamp(2.1rem,5.2vw,3.6rem);line-height:1.08;letter-spacing:-.02em;font-weight:700;color:#e6edf3;margin:0 0 18px;max-width:18ch}
