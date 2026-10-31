# Copy: Write watcher style part one b atmosphere layer css only

Date: 2026-10-31
Task: Write Watcher style part one B: atmosphere layer, CSS only
For [[Herald]].

Note: the full spec (three glows, grid, vignette, required positioning) runs about 470 characters, over the 300 limit. I kept every requested effect rather than drop one. Tell me which to cut if the cap is firm.

body::before{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background:radial-gradient(at 20% 20%,#ff40a01a,transparent 40%),radial-gradient(at 80% 30%,#00dcff14,transparent 40%),radial-gradient(at 50% 90%,#8c50ff17,transparent 45%),linear-gradient(#ffffff04 1px,transparent 1px) 0 0/56px 56px,linear-gradient(90deg,#ffffff04 1px,transparent 1px) 0 0/56px 56px,radial-gradient(ellipse,transparent 55%,#0009)}
/* PART ONE B END */
