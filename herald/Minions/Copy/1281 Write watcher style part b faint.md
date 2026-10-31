# Copy: Write watcher style part b faint 56px grid at 1

Date: 2026-10-31
Task: Write Watcher style part B: faint 56px grid at 1.5 percent white and edge vignette using body::after, then the closing style tag. No opening style tag. Under 70
For [[Herald]].

body::after {
  content: "";
  position: fixed;
  inset: 0;
  z-index: -2;
  pointer-events: none;
  background-image:
    radial-gradient(ellipse at center, rgba(0,0,0,0) 40%, rgba(0,0,0,.55) 100%),
    linear-gradient(rgba(255,255,255,.015) 1px, transparent 1px),
    linear-gradient(90deg, rgba(255,255,255,.015) 1px, transparent 1px);
  background-size: 100% 100%, 56px 56px, 56px 56px;
  background-attachment: fixed;
}
</style>
