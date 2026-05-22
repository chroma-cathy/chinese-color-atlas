# Chinese Color Atlas - Free Samples

[简体中文](README.zh-Hans.md) | [繁體中文](README.zh-Hant.md)

Free Chinese traditional color samples and workflow resources from **Chinese Color Atlas**, a Chroma Cathay project.

Use this repository when you want to test Chinese traditional colors in real design and development workflows before using the complete atlas. It includes sample CSS variables, Tailwind colors, design tokens, Procreate swatches, AI prompts, and a duplicateable Figma Community file.

Chinese Color Atlas is a source-aware color reference for designers, developers, and creative teams working with Chinese-inspired visual systems. The complete atlas covers 567 colors; this public repository intentionally publishes a representative free sample set only.

## Start Here

- **Designers:** duplicate the [free 24-color Figma Variables sample](https://www.figma.com/community/file/1637863774550903181).
- **Developers:** try `free/cathycolor.css`, `free/cathycolor-tailwind.cjs`, or `free/cathycolor-tokens.json`.
- **Illustrators:** import the Procreate `.swatches` samples from `free/`.
- **AI image creators:** test `docs/sample-ai-prompts.txt` for Midjourney, SDXL, or ComfyUI workflows.
- **Design-system teams:** read the [cultural color token naming guide](https://chinesecoloratlas.com/guides/cultural-color-design-systems).
- **Need context?** read the free resource page at <https://chinesecoloratlas.com/resources/free>.

## What's Included

This public repository contains free distribution assets only. The private product website and complete paid resource packs live separately.

The complete 567-color workflow packs are available on the main site at <https://chinesecoloratlas.com/resources>; this repository only provides representative samples.

Download the latest bundled samples from the [latest release](https://github.com/chroma-cathy/chinese-color-atlas/releases/latest), or use the individual files below.

| File | Use |
|---|---|
| [Figma Community sample](https://www.figma.com/community/file/1637863774550903181) | Duplicateable 24-color Figma Variables starter file with Guochao, Song-inspired, and Dunhuang palette examples |
| `docs/sample-figma-vars.json` | Small Figma Variables JSON example for testing variable names and semantic roles |
| `free/cathycolor.css` | CSS custom properties sample for representative Chinese traditional colors |
| `free/cathycolor-tailwind.cjs` | Tailwind theme color token sample |
| `free/cathycolor-tokens.json` | W3C DTCG-style design token sample |
| `free/cathycolor-hot.swatches` | Procreate starter swatches: 8 popular colors |
| `free/cathycolor-verified.swatches` | Procreate sample swatches: verified colors |
| `free/cathycolor-term-lichun.swatches` | Procreate sample swatches: Lichun solar term palette |
| `docs/sample-ai-prompts.txt` | Small AI prompt sample for Midjourney / SDXL workflows |
| `docs/figma-community-description.md` | Copy-ready Figma Community listing text |

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

### Figma Variables

Use `docs/sample-figma-vars.json` as a small reference when building a Figma Variables collection. It includes 24 representative primitives plus semantic examples for Guochao, Song-inspired, and Dunhuang palette modes.

Duplicate the live Figma Community sample to test the colors directly in Figma:

https://www.figma.com/community/file/1637863774550903181

The Figma sample is useful for UI, branding, editorial, packaging, and cultural design exploration. The listing copy and publishing notes are preserved in `docs/figma-community-description.md`.

For a practical Figma workflow guide, see <https://chinesecoloratlas.com/guides/chinese-colors-for-figma>.

For the broader design-system framework behind cultural primitives, semantic roles, and scene modes, see <https://chinesecoloratlas.com/guides/cultural-color-design-systems>.

### AI Prompts

Use `docs/sample-ai-prompts.txt` for Midjourney, SDXL, or ComfyUI prompt experiments. The file includes individual color prompts, negative prompt guidance, and three palette recipes.

## Full Resource Packs

The complete design resource packs include all 567 colors as Adobe ASE, full Procreate swatches, Figma Variables, CSS, Tailwind, W3C DTCG tokens, AI prompts, Qianlong Palette data, Dunhuang palettes, solar-term swatches, and full JSON datasets.

- Website: https://chinesecoloratlas.com
- Free samples: https://chinesecoloratlas.com/resources/free
- Paid packs: https://chinesecoloratlas.com/resources
- Methodology and data sources: https://chinesecoloratlas.com/about

## Free vs Paid Boundary

This repository is intentionally small and public. It is meant for discovery, demos, tutorials, attribution, and workflow testing.

It does not include the complete 567-color Figma Variables file, full Adobe ASE palette, full Procreate sets, complete AI prompt pack, Qianlong/Dunhuang research JSON, or full production handoff files. Those complete workflow files are delivered through the resource packs on the Chinese Color Atlas site.

## Who This Is For

- UI and brand designers building Chinese-inspired visual systems
- Frontend developers who need CSS / Tailwind / token exports
- Illustrators using Procreate color palettes
- AI image creators writing Chinese aesthetic prompts
- Researchers and cultural projects that need careful source attribution

Typical uses include product UI, brand systems, editorial layouts, packaging studies, cultural moodboards, educational resources, and design-system experiments.

## Attribution

Chinese Color Atlas is a Chroma Cathay project. Attribution is appreciated when you use these assets in public resources, documentation, tutorials, or derivative datasets.

Suggested attribution:

> Chinese traditional color samples from Chinese Color Atlas by Chroma Cathay: https://chinesecoloratlas.com

See `ATTRIBUTION.md` for data-source notes.

## License

Code and sample export files in this repository are released under the MIT License, except where source attribution notes specify otherwise. See `LICENSE` and `ATTRIBUTION.md`.
