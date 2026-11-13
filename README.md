# WWWave / 首位传媒 — Kinetic Media prototype

Static prototype of the WWWave studio site, packaged for browser review.

- `index.html` — the whole site (single entry, all CSS/JS inline)
- `assets/img`, `assets/video`, `assets/fonts` — media split out of the original
  single-file build so the page paints immediately instead of waiting for
  ~32 MB of base64 to download
- `films/` — case study films referenced by the project detail views

Originals live outside this repo and were not modified. Films above 25 MB were
re-encoded once (H.264, CRF 32, faststart) to stay inside GitHub's per-file limit;
smaller films are byte-identical copies.

Hosted with GitHub Pages from the repository root.
