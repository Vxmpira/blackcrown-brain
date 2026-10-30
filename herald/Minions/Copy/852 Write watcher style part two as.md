# Copy: Write watcher style part two as raw css only under

Date: 2026-10-29
Task: Write Watcher style part two as raw CSS only, under 700 characters, no style tags.
For [[Herald]].

header{display:flex;align-items:center;gap:.6rem}
header svg{width:32px;height:32px}
.ix-hero{padding:clamp(2rem,6vw,4rem) 0}
.ix-hero h1{font-size:clamp(1.8rem,4.5vw,3rem);margin:0 0 .5rem;color:#f2f2f5}
.ix-prose{max-width:72ch;color:#c9ccd6;line-height:1.6}
a{color:#ff2d8f}
.ix-grid{display:grid;grid-template-columns:1fr 1fr;gap:1rem}
.ix-panel{background:#11131a;border:1px solid #232634;border-radius:12px;padding:1.2rem}
.ix-chips{display:flex;flex-wrap:wrap;gap:.5rem}
.ix-chip{border:1px solid #2a2e3d;border-radius:999px;padding:.25rem .75rem;color:#e6e8ef}
@media(max-width:699px){.ix-grid{grid-template-columns:1fr}}
