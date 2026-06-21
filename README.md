# ENGINE page redesign sketch — 2026-06-21

Open **`index.html`** in a browser. Click the device, then drive it:

- `1`–`5` switch layout · `q`/`e` switch engine
- `← → ↑ ↓` navigate · `ENTER` open/drill · `ESC` back · `w`/`s` nudge a value

Eight tabs:

- **0 · TODAY** — the shipped v3 layout, for A/B. The one in use today.
- **1 · PANELS** *(boxes + glyphs)* — old boxes back, but each leads with a *picture* (waveform, env curve, step grid, comp/gain), spread across the whole screen. ENTER drills a panel open.
- **2 · FOCUS** *(SOURCE-page model)* — calm one-value list on the left, one big live preview on the right that becomes whatever you touch.
- **★ 3 · BOXES** *(refined)* — each section is its own bordered card with a boxed name chip; only the envelope keeps a visualizer. Spacious, walled-off, calm.
- **4 · HERO** *(bold)* — the engine is the star: big visualizer on top, tiny summary chips below, params bloom only when you ask.
- **★ 5 · RASTER** *(refined, mixer-page family)* — section columns + a clean full value matrix, one family with the MIXER page; only the ENV column shows its curve. Densest.
- **6 · ROW VIZ** — today's stream with a per-category visualizer under each row. *(Not a keeper — too busy.)*
- **★ 7 · 7×TODAY** *(refined)* — today's density + fast nav, with boxed section labels + dividers for separation; the envelope curve is the one kept viz (inline under the ENV row). Closest to today.

The **★ three** (3, 5, 7) are the ones liked + refined per feedback: boxes/separation added, decorative visualizers dropped, only the envelope kept.

## The diagnosis (why it feels dense)

The v3 page throws **25 label+value pairs into the top third as one block**, leaves a **dead void in the middle**, and gives the eye **no anchor**. The old 2×2 cards won because each section was a box with a picture, so you focused on one thing. These four sketches each fix density / anchor / wasted-space differently.

## Reference screenshots (real app, current build)

- `01_new_collapsed.png` `02_new_nav.png` `03_new_fold.png` — current v3 in its three states
- `04_old_cards.png` — the old 2×2 card layout (the boxes Tom misses)
- `05_miplaits.png` `06_wave.png` `07_drum.png` — current v3 on other engines
- `variant*.png` — stills of each proposal

The sketch is faithful to the live design system: 480×320, Spleen-ish mono, real param values, real section colours (SOURCE cyan / VOICE violet / ENV coral / MIX grey / PATTERN amber / focus red).
