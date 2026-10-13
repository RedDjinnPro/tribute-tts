# Tribute · Tabletop Simulator assets

Published by the project's **Tribute - TTS Export** page. Don't edit these files by hand; the next publish overwrites them.

- `Tribute.json` — the TTS save (publish.sh copies it into your TTS Saves folder).
- `manifest.json` — the current version of every asset; the save's loader script reads it on load.
- `cards/` — deck sheets and backs.
- `.nojekyll` — tells GitHub Pages to serve the files as they are.

The save loads every image from **GitHub Pages** (`https://<owner>.github.io/<repo>/`), not raw.githubusercontent.com, which rate-limits a table's burst of image requests. Pages must be on: Settings › Pages › Deploy from a branch › main / (root).

To publish a new export: `cd ~/tribute-tts && ./publish.sh`
