# Copy: Write watcher style rules part one as raw css under

Date: 2026-10-30
Task: Write Watcher style rules part one as raw CSS, under 700 characters.
For [[Herald]].

:root{--ix-pink:#ff2d8f;--ix-ink:#e9e6f0;--ix-mute:#9b95ab;--ix-line:rgba(255,255,255,.08)}
*,*::before,*::after{box-sizing:border-box}
html{margin:0;background:#0b0a12}
body{margin:0;color:var(--ix-ink);font:16px/1.6 system-ui,sans-serif}
body::before{content:'';position:fixed;inset:0;z-index:-1;pointer-events:none;background:radial-gradient(40vw 35vh at 15% 10%,#ff2d8f33,#0000),radial-gradient(45vw 40vh at 85% 30%,#8c50ff26,#0000),radial-gradient(35vw 30vh at 50% 95%,#ff2d8f1a,#0000),radial-gradient(#0000 60%,#0008),linear-gradient(rgba(255,255,255,.015) 1px,#0000 1px) 0 0/56px 56px,linear-gradient(90deg,rgba(255,255,255,.015) 1px,#0000 1px) 0 0/56px 56px}
