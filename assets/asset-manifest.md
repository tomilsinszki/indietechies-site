# Generated asset manifest

| Path | Role | Dimensions | Media rationale | Source category |
| --- | --- | ---: | --- | --- |
| `assets/proof-decision-note.webp` | First contact-sheet proof frame: an illustrative top-down decision note with the approved problem, goal, and measure copy. | 960 × 640 px | A generated raster preserves the tactile paper, pen, wood, handwriting, and documentary-photography character that would be artificial and brittle to recreate in CSS. It is illustrative and is not presented as real customer or performance evidence. | `generated` |
| `assets/proof-paper-texture.webp` | Seamless-looking, extremely low-contrast warm proof-paper texture for broad page surfaces. | 1024 × 1024 px | A compact raster provides organic, non-programmatic fiber variation while keeping the page quiet enough for high-contrast semantic content. | `generated` |
| `assets/tom-portrait.jpg` | Identity portrait in the hero contact frame. | 3024 × 2268 px | Tom's supplied photograph makes the page visibly personal and provides direct identity proof. It is cropped responsively in CSS but otherwise unchanged. | `user-supplied` |

## Prompt provenance

- `assets/proof-decision-note.prompt.txt` contains the exact generation prompt; `assets/proof-decision-note.webp.json` is the prompt sidecar produced by the Impeccable prompt embedder.
- `assets/proof-paper-texture.prompt.txt` contains the exact generation prompt; `assets/proof-paper-texture.webp.json` is the prompt sidecar produced by the Impeccable prompt embedder.
- Both final rasters were generated with the built-in image generation tool, using `.impeccable/mocks/homepage-option-2.webp` only as a style and palette reference, then converted to WebP.
- `assets/tom-portrait.provenance.txt` records the supplied photograph's non-generated source, and the same provenance is embedded in the shipping JPEG.

## Remains semantic code

The workflow map, terminal checklist, all UI text and controls, and all icons remain semantic HTML/CSS rather than generated pixels. This keeps meaning, focus behavior, accessibility, responsive layout, and copy maintenance in code.

## Limitations

- The decision note is generated editorial illustration, not documentary evidence of a real workflow result.
- The paper texture is visually subtle and seam-free at normal display scale, but generated texture cannot guarantee mathematically identical opposite-edge pixels. Keep it low-opacity or behind the base `#F2EFE7` color so any repetition remains imperceptible.
