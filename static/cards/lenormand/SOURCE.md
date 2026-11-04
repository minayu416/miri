# Game of Hope — Lenormand card artwork

## Lighter warm beige variation

`back-warm-light.webp` is an alternative lighter variation. The current card-back asset is `back-warm-large.webp` (warm beige with the enlarged central ornament). Edited with built-in imagegen from `back-warm-large.webp`, then exported to 480 × 720 WebP (quality 88). Earlier variations remain available. This is a supplied modern design, separate from the historical public-domain fronts.

Final edit prompt:

> Use case: precise-object-edit. Edit target: this warm beige botanical Lenormand card back. Change ONLY the background paper color: make it slightly whiter/brighter, as if mixing about 12 percent warm ivory into the existing beige. Preserve its existing warm beige hue, subtle parchment texture and warm atmosphere; do not turn it pure white, gray or yellow. Keep ALL botanical branches, central star, corner stars, thin rounded border, their antique gold color, contrast, exact shapes, scale and positions unchanged. Preserve the enlarged central motif and 2:3 portrait composition. Flat edge-to-edge asset, no perspective, no text, no new elements. This is a restrained background-only lightening.

- Work: Das Spiel der Hofnung (The Game of Hope), 1799
- Creator: Johann Kaspar Hechtel
- Collection/source: The British Museum, 1896,0501.495
- File description and rights: https://commons.wikimedia.org/wiki/File:Das_Spiel_der_Hofnung_(The_Game_of_Hope).png
- Original download: https://upload.wikimedia.org/wikipedia/commons/a/a6/Das_Spiel_der_Hofnung_%28The_Game_of_Hope%29.png
- Rights marking: Public Domain Mark 1.0, https://creativecommons.org/publicdomain/mark/1.0/
- Wikimedia identifies the file as public domain in its country of origin and the United States, and free of known copyright restrictions.
- Retrieved: 2026-11-01
- Original: 3900 × 4900 PNG, SHA-1 fb42993d759f0a7b391fc08e8867e7c450cb8905

Processing: cropped each of the 36 cards from the original scan; retained original printed numbers, artwork, aged paper and edges. Scaled proportionally onto white 560 × 770 canvases and exported WebP (quality 92). No generative repainting or text replacement. Slight original card tilts are retained. Each manifest entry records the source crop rectangle (left, top, right, bottom) and the matching backend card ID (1–36).

To reproduce, download the original outside public/ and run `python scripts/crop-lenormand.py SOURCE.png` with Pillow installed. The source sheet is intentionally excluded from the website assets to avoid shipping an additional 29.4 MB file.

These rights information and edits relate to the card artwork, not the application code or reading interpretations.

## Separate card-back asset

`back.webp` is separate from the historical card fronts above. It was supplied by the project owner as `Minimalist Gold Botanical Lenormand Card Back.png` and resized proportionally from 1024 × 1536 to 480 × 720, then encoded as WebP (quality 88). The public-domain statement for the 1799 card fronts does not describe this supplied card-back asset.

### Warm beige variation

`back-warm.webp` is the currently used variation, edited with the built-in imagegen tool from the supplied original, then resized to 480 × 720 and encoded as WebP (quality 88). `back.webp` retains the previous ivory version.

Final edit prompt:

> Use case: precise-object-edit. Edit target: the supplied botanical Lenormand card back. Make ONLY a subtle palette adjustment for use over a dark navy website: replace the bright ivory paper with muted warm beige parchment (#d8c6a6 approximate), and deepen the existing gold botanical linework, border and stars to antique gold (#9b763e approximate) for small-screen legibility. Preserve exactly the botanical motif, all leaves, central star, four corner stars, rounded thin inset border, original 2:3 portrait composition, broad negative space and delicate paper texture. Flat edge-to-edge card-back asset, no mockup, no perspective, no text, no new elements. Do not make a dark blue version. Keep refined and understated.

### Larger central ornament

`back-warm-large.webp` is now used by the shuffle pile, selection deck and selected slots. Created using the built-in imagegen edit tool from `back-warm.webp`; exported at 480 × 720, WebP quality 88. The smaller-ornament version is retained.

Final edit prompt:

> Use case: precise-object-edit. Edit this warm beige botanical Lenormand card back. Change ONLY the scale of the CENTRAL group consisting of the two botanical branches and the central four-point star: enlarge that entire group uniformly by approximately 18% around the exact canvas center. Keep its shape, orientation, spacing within the group and delicate antique gold lines. Keep the thin rounded inset gold border and all FOUR CORNER STARS exactly in their current positions and sizes. Preserve the existing muted warm beige parchment color and texture, antique gold palette, 2:3 portrait aspect ratio and flat edge-to-edge layout. No text, no added elements, no mockup, no global zoom or crop. Only central ornament larger.
