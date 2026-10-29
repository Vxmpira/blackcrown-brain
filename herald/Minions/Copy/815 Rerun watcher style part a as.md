# Copy: Rerun watcher style part a as raw css closed with

Date: 2026-10-29
Task: Rerun Watcher style part A as raw CSS, closed with </style>.
For [[Herald]].

<style>
:root{
--ink:#e8ecf3;
--muted:#8a94a6;
--line:#1d2433;
--pink:#ff2d8f;
--cyan:#27d4ff;
--bg:#06080d;
}
*,*::before,*::after{box-sizing:border-box}
html{background:var(--bg);color:var(--ink);-webkit-text-size-adjust:100%}
body{margin:0;min-height:100vh;font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6;overflow-x:hidden}
body::before{
content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;
background:
radial-gradient(60% 50% at 15% 0%,rgba(255,45,143,.14),transparent 70%),
radial-gradient(55% 45% at 90% 10%,rgba(39,212,255,.12),transparent 70%),
radial-gradient(50% 40% at 50% 100%,rgba(39,212,255,.08),transparent 70%);
}
body::after{
content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;
background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);
background-size:56px 56px;
box-shadow:inset 0 0 160px 40px rgba(0,0,0,.75);
}
</style>
