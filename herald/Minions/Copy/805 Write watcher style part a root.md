# Copy: Write watcher style part a root vars reset html and

Date: 2026-10-29
Task: Write Watcher style part A: :root vars, reset, html and body base, body::before glows. Under 700 characters. End with the closing tag seen.
For [[Herald]].

<style>
:root{--bg:#0b0b12;--ink:#e9e9f0;--muted:#9a9ab0;--pink:#ff2d8f;--blue:#3a6cff;--gold:#c9a227}
*{box-sizing:border-box;margin:0;padding:0}
html{background:var(--bg);color:var(--ink)}
body{min-height:100vh;font:16px/1.6 system-ui,sans-serif;overflow-x:hidden;background:var(--bg)}
body::before{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background:radial-gradient(50vw 40vw at 0 0,rgba(255,45,143,.16),transparent 60%),radial-gradient(50vw 40vw at 100% 0,rgba(58,108,255,.14),transparent 60%)}
</style>
