# Chinese Color Atlas

Public free Chinese traditional color tokens, samples, and design resources from **Chinese Color Atlas**, a Chroma Cathy project.

Chinese Color Atlas curates 567 Chinese traditional colors for designers, developers, and AI creators, with practical exports for modern design workflows.

## What's Included

This public repository contains free distribution assets only. The private product website and complete paid resource packs live separately.

Download the latest bundled samples from the [v1.0.0 release](https://github.com/chroma-cathy/chinese-color-atlas/releases/tag/v1.0.0), or use the individual files below.

| File | Use |
|---|---|
| `free/cathycolor.css` | CSS custom properties for Chinese traditional colors |
| `free/cathycolor-tailwind.cjs` | Tailwind theme color tokens |
| `free/cathycolor-tokens.json` | W3C DTCG-style design tokens |
| `free/cathycolor-hot.swatches` | Procreate starter swatches: 8 popular colors |
| `free/cathycolor-verified.swatches` | Procreate sample swatches: verified colors |
| `free/cathycolor-term-lichun.swatches` | Procreate sample swatches: Lichun solar term palette |
| `docs/sample-figma-vars.json` | Small Figma Variables JSON example |
| `docs/sample-ai-prompts.txt` | Small AI prompt sample for Midjourney / SDXL workflows |

## Quick Use

### CSS

```css
@import "./free/cathycolor.css";

.card {
  background: var(--cc-yanzhi);
  color: var(--cc-yuebai);
}
```

### Tailwind

```js
const cathyColor = require('./free/cathycolor-tailwind.cjs')

module.exports = {
  theme: {
    extend: {
      colors: cathyColor.colors,
    },
  },
}
```

### Procreate

Download one of the `.swatches` files from `free/`, then open it on iPad with Procreate installed.

## Full Resource Packs

The complete design resource packs include Adobe ASE, Procreate swatches, Figma Variables, CSS, Tailwind, W3C DTCG tokens, AI prompts, Qianlong Palette data, Dunhuang palettes, solar-term swatches, and full JSON datasets.

- Website: https://chinesecoloratlas.com
- Free samples and paid packs: https://chinesecoloratlas.com/resources
- Methodology and data sources: https://chinesecoloratlas.com/about

## Who This Is For

- UI and brand designers building Chinese-inspired visual systems
- Frontend developers who need CSS / Tailwind / token exports
- Illustrators using Procreate color palettes
- AI image creators writing Chinese aesthetic prompts
- Researchers and cultural projects that need careful source attribution

## Attribution

Chinese Color Atlas is a Chroma Cathy project. Attribution is appreciated when you use these assets in public resources, documentation, tutorials, or derivative datasets.

Suggested attribution:

> Chinese traditional color samples from Chinese Color Atlas by Chroma Cathy: https://chinesecoloratlas.com

See `ATTRIBUTION.md` for data-source notes.

## License

Code and sample export files in this repository are released under the MIT License, except where source attribution notes specify otherwise. See `LICENSE` and `ATTRIBUTION.md`.
