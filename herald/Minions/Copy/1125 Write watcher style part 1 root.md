# Copy: Write watcher style part 1 root vars reset body glow

Date: 2026-10-30
Task: Write Watcher style part 1: root vars, reset, body, glow layers. Under 700 characters, no closing style tag yet.
For [[Herald]].

<style>
:root{--pink:#ff2d8f;--ink:#0b0b10;--text:#ececf3;--muted:#a3a3b3;--line:rgba(255,255,255,.09)}
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
body{background:var(--ink);color:var(--text);font:16px/1.6 system-ui,sans-serif;position:relative;overflow-x:hidden}
body::before,body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none}
body::before{background:radial-gradient(60% 45% at 85% 0%,rgba(255,45,143,.2),transparent 70%),radial-gradient(50% 40% at 0% 100%,rgba(255,45,143,.1),transparent 70%)}
body::after{background:radial-gradient(120% 90% at 50% 50%,transparent 55%,rgba(0,0,0,.6))}
