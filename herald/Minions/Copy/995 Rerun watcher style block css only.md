# Copy: Rerun watcher style block css only under 40 lines no

Date: 2026-10-30
Task: Rerun Watcher style block: CSS only, under 40 lines, no script, end with closing style tag.
For [[Herald]].

<style>
:root{--bg:#07070c;--pink:#ff2d8f;--cool:#2dd4ff;--ink:#e9e9f2;--mute:#9a9ab0}
*,*::before,*::after{box-sizing:border-box}
html,body{margin:0;padding:0}
html{background:var(--bg);color:var(--ink);-webkit-text-size-adjust:100%}
body{min-height:100vh;background:var(--bg);color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",sans-serif;line-height:1.6;position:relative;isolation:isolate;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;pointer-events:none;z-index:-1;background:radial-gradient(circle at 15% 10%,rgba(255,45,143,.18),transparent 45%)}
body::after{content:"";position:fixed;inset:0;pointer-events:none;z-index:-1;background:radial-gradient(circle at 85% 90%,rgba(45,212,255,.14),transparent 50%)}
p{color:var(--mute)}
</style>
