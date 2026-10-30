# Copy: Write watcher style part one as raw css under 700

Date: 2026-10-30
Task: Write Watcher style part one as raw CSS, under 700 characters, no style tags, no em dashes.
For [[Herald]].

:root{--ix-pink:#ff2d8f;--ix-ink:#eae8f4;--ix-line:rgba(255,255,255,.08)}
body{margin:0;color:var(--ix-ink);background:#0c0b16}
body::before{content:"";position:fixed;inset:0;z-index:-1;background:radial-gradient(circle at 20% 0,#ff2d8f33,transparent 40%),radial-gradient(ellipse,transparent 60%,#0008),linear-gradient(90deg,#ffffff04 1px,transparent 1px) 0 0/56px 56px,linear-gradient(#ffffff04 1px,transparent 1px) 0 0/56px 56px}
.ix-header{display:flex;padding:20px 24px}
.ix-hero{margin:auto;padding:72px 24px;max-width:1060px}
.ix-hero h1{font-size:clamp(2.2rem,6vw,4rem)}
.ix-lede{max-width:62ch;opacity:.85}
.ix-cta{padding:14px 26px;border:1px solid var(--ix-pink);color:var(--ix-ink)}
