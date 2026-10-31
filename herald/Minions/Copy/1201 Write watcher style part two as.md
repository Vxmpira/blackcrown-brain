# Copy: Write watcher style part two as css rules only no

Date: 2026-10-31
Task: Write Watcher style part two as CSS rules only, no style tags, under 600 characters, ending with the line /* END PART TWO */
For [[Herald]].

.wt-wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
h1{font-size:clamp(28px,5vw,52px);line-height:1.1}
h2{font-size:clamp(22px,3.4vw,34px);line-height:1.2}
.prose{max-width:75ch}
.tablewrap{overflow-x:auto;border-radius:12px}
.wt-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:20px}
@media (max-width:699px){.wt-grid{grid-template-columns:1fr}}
/* END PART TWO */
