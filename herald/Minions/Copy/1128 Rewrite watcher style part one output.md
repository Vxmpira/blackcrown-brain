# Copy: Rewrite watcher style part one output only the style block

Date: 2026-10-30
Task: Rewrite Watcher style part one. Output only the style block from the opening style tag through the closing style tag.
For [[Herald]].

<style>
:root{--pink:#ff2d8f;--ink:#0b0b10;--text:#ececf3;--muted:#a3a3b3;--line:rgba(255,255,255,.09)}
*,*::before,*::after{box-sizing:border-box}
body{background:var(--ink);color:var(--text)}
body::before,body::after{content:"";position:fixed;inset:0}
body::before{z-index:-2;background:radial-gradient(circle at 15% 10%,rgba(255,45,143,.18),transparent 40%),radial-gradient(circle at 85% 90%,rgba(255,45,143,.12),transparent 45%)}
body::after{z-index:-1;background:linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px) 0 0/56px 56px,linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px) 0 0/56px 56px;box-shadow:inset 0 0 160px #0008}
</style>
