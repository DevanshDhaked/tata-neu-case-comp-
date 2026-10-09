# Neu Nights: 7-slide pitch deck

Concept proposal for CaseCom 2026 (Tata Neu product case). Not affiliated with Tata Digital.

## Files

| File | What it is |
|---|---|
| `index.html` | The deck. Self-contained, works offline (fonts and logo are in `assets/`). |
| `neu-nights-deck.pdf` | Print-ready export, one 16:9 slide per page, built from 2× renders so it matches the screen exactly. |
| `neu-nights-deck.pptx` | Image-based PowerPoint (one full-slide picture per slide). Only present if `python-pptx` was installed when exporting. Not editable text. |
| `renders/slide-N.png` | 2560 × 1440 PNG of every slide. |
| `sources-and-assumptions.md` | Sources, modeled numbers, proposed targets and open product decisions. |
| `tools/render.py` | Re-renders the PNGs, PDF and PPTX. |

## Present

1. Open `index.html` in Chrome, Edge, Safari or Firefox (double-click works; no server needed).
2. Press **F** (or the corner button) for full screen.
3. Navigate: **→ / Space / Enter / Page Down** next, **← / Page Up** previous, **Home / End** first/last. Swipe on touch screens.
4. The controls fade out after 2 s without mouse movement. `index.html#5` opens slide 5 directly.

The slide is designed at 1280 × 720 and scales to any screen without scrolling.

## Export

- **Recommended:** use the included `neu-nights-deck.pdf`.
- **Regenerate everything** (after edits): `python3 tools/render.py` from this folder. Needs Python 3 with `playwright` (`pip install playwright && playwright install chromium`); `python-pptx` is optional for the `.pptx`.
- **Browser print fallback:** Ctrl/Cmd + P → Save as PDF, margins *None*, *Background graphics* on. The print stylesheet gives one slide per page, but browser PDF engines flatten a few glow effects, so the rendered PDF looks better.
