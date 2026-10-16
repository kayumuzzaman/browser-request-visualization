# Browser Request Visualization

One page that visualizes what happens when you type `google.com` and press <kbd>Enter</kbd> — from keypress to pixels.

**Live:** https://kayumuzzaman.github.io/browser-request-visualization/

A single self-contained `index.html` (plus this README). No build, no dependencies — just open it.

## What it shows

24 stages across 6 stops: Keys → OS → Browser decides → Network → Server → Browser draws. Plain-words summary per stage, with diagrams and verifiable details.

## Credit

Visualization inspired by [alex/what-happens-when](https://github.com/alex/what-happens-when) — the classic deep-dive on the same question. This is a visual retelling with updated info (last checked Oct 2026), not a fork.

## Run locally

```bash
open index.html
# or
python3 -m http.server 8000
# → http://localhost:8000
```
