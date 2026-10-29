# Copy: Write watcher style part c body after grid and vignette

Date: 2026-10-29
Task: Write Watcher style part C: body::after grid and vignette, ending </style>.
For [[Herald]].

<style>
body::after {
  content: "";
  position: fixed;
  inset: 0;
  z-index: -1;
  pointer-events: none;
  background:
    radial-gradient(ellipse at center, transparent 55%, rgba(0,0,0,0.55) 100%),
    repeating-linear-gradient(0deg, rgba(255,255,255,0.015) 0 1px, transparent 1px 56px),
    repeating-linear-gradient(90deg, rgba(255,255,255,0.015) 0 1px, transparent 1px 56px);
}
</style>
