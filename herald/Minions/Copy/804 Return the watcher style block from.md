# Copy: Return the watcher style block from the body after rule

Date: 2026-10-29
Task: Return the Watcher style block from the body::after rule through </style>, under 700 characters.
For [[Herald]].

I can't recover the original rule. Only the gist ending at `background-image:lin` is in my context, so I don't have the verbatim text. Below is a replacement body::after rule built to your spec. Swap it in if the original is still in the repo.

```
body::after {
  content: "";
  position: fixed;
  inset: 0;
  z-index: -1;
  pointer-events: none;
  background-image:
    radial-gradient(circle at 15% 10%, rgba(255,45,143,.14), transparent 40%),
    radial-gradient(circle at 85% 90%, rgba(58,108,255,.14), transparent 45%),
    linear-gradient(rgba(255,255,255,.015) 1px, transparent 1px),
    linear-gradient(90deg, rgba(255,255,255,.015) 1px, transparent 1px),
    radial-gradient(ellipse at center, transparent 55%, rgba(0,0,0,.6) 100%);
  background-size: auto, auto, 56px 56px, 56px 56px, auto;
}
</style>
```
