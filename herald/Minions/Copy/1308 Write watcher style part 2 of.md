# Copy: Write watcher style part 2 of 2 grid chips figure

Date: 2026-11-01
Task: Write Watcher style part 2 of 2: grid, chips, figure, tablewrap, h1 and wrap rules, under 650 characters, closing brace seen.
For [[Herald]].

.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
.grid{display:flex;flex-wrap:wrap;gap:16px;align-items:center;justify-content:space-between}
@media (max-width:700px){.grid{flex-direction:column;align-items:stretch}}
h1{font-size:clamp(28px,5vw,44px);line-height:1.15;margin:0 0 16px}
p{max-width:68ch}
.chip{display:inline-block;padding:4px 12px;border:1px solid #ff2d8f55;border-radius:999px;font-size:13px}
.figure{background:#ffffff08;border:1px solid #ffffff14;padding:20px;border-radius:12px}
.tablewrap{overflow-x:auto;border-radius:12px;width:100%}
a{color:#ff2d8f}
