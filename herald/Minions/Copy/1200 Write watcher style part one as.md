# Copy: Write watcher style part one as css rules only no

Date: 2026-10-31
Task: Write Watcher style part one as CSS rules only, no style tags, under 600 characters, ending with the line /* END PART ONE */
For [[Herald]].

:root{--bg:#07070c;--ink:#e9ecf5;--mute:#8a90a6;--pink:#ff2d8f;--cyan:#2de2ff;--violet:#8c50ff}
html,body{margin:0;padding:0}
body{background:var(--bg);color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6;min-height:100vh;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background:radial-gradient(circle at 15% 20%,rgba(255,45,143,.18),transparent 45%),radial-gradient(circle at 85% 30%,rgba(45,226,255,.14),transparent 50%),radial-gradient(circle at 50% 90%,rgba(140,80,255,.16),transparent 55%),linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:auto,auto,auto,56px 56px,56px 56px}
/* END PART ONE */
