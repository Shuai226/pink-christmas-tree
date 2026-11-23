# Pink Christmas Tree · To: Zhang Aoyun

A single-file interactive pink particle Christmas tree webpage, rendered with Canvas 2D pseudo-3D projection.

## Preview

- Pink particle cone tree with a glowing top star, spiral ribbon, gifts and baubles
- Falling snow and twinkling starfield on a deep plum night sky
- English title **Merry Christmas** and dedication **To: Zhang Aoyun**
- Particles spiral into the tree on load; click anywhere to burst pink sparkles

## Run

No build step, no dependencies. Open `pink-christmas-tree.html` directly in a browser, or serve it locally:

```bash
npx serve .
```

Debug query params:

- `?ready=1` — skip the opening particle convergence animation

## Customize

| What | Where in `pink-christmas-tree.html` |
| --- | --- |
| Dedication name | `.to-sign .to b` — change `Zhang Aoyun` |
| Title / wish line | `.hero` block |
| Particle colors | `palette` object in the script (`main`, `deep`, `pearl`, `gift`) |
| Particle count | `PARTICLE_COUNT` constant |
| Tree size / shape | `TREE_H`, `TREE_R` constants |

## Tech

- Vanilla HTML / CSS / JavaScript, one self-contained file
- Canvas 2D, pseudo-3D rotation + perspective projection
- No CDN, no framework, no camera or network permission required
