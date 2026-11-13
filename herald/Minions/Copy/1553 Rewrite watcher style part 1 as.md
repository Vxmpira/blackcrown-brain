# Copy: Rewrite watcher style part 1 as raw css under 600

Date: 2026-11-13
Task: Rewrite Watcher style Part 1 as raw CSS, under 600 characters, no script, ends at the glow rules
For [[Herald]].

body{margin:0;background:linear-gradient(#0d0d16,#07070c)}
body::before,body::after,.glow{position:fixed;inset:0;pointer-events:none;z-index:-1}
body::before{content:"";background:linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px) 0 0/56px 56px,linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px) 0 0/56px 56px}
body::after{content:"";background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.6))}
.glow{background:radial-gradient(circle at 15% 10%,rgba(255,45,143,.14),transparent 30%),radial-gradient(circle at 85% 30%,rgba(255,45,143,.1),transparent 25%)}
