# Chinese Color Atlas - 免费样本

[English](README.md) | [繁體中文](README.zh-Hant.md)

来自 **Chinese Color Atlas** 的中国传统色免费样本与工作流资源。Chinese Color Atlas 是 Chroma Cathay 旗下项目。

如果你想先在真实设计和开发流程中测试中国传统色，再决定是否使用完整色谱，可以从这个仓库开始。这里包含 CSS 变量样本、Tailwind 颜色、设计 Token、Procreate 色板、AI 提示词，以及可复制的 Figma Community 文件。

Chinese Color Atlas 是面向设计师、开发者和创意团队的、带来源意识的中国传统色参考。完整色谱覆盖 567 个颜色；这个公开仓库只发布具有代表性的免费样本。

## 从这里开始

- **设计师：** 复制 [24 色免费 Figma Variables 样本](https://www.figma.com/community/file/1637863774550903181)。
- **开发者：** 试用 `free/cathycolor.css`、`free/cathycolor-tailwind.cjs` 或 `free/cathycolor-tokens.json`。
- **插画师：** 导入 `free/` 目录中的 Procreate `.swatches` 样本。
- **AI 图像创作者：** 用 `docs/sample-ai-prompts.txt` 测试 Midjourney、SDXL 或 ComfyUI 工作流。
- **设计系统团队：** 阅读[文化色彩 Token 命名指南](https://chinesecoloratlas.com/guides/cultural-color-design-systems)。
- **需要上下文？** 阅读免费资源页：<https://chinesecoloratlas.com/resources/free>。

## 包含内容

这个公开仓库只包含免费分发资产。私有产品网站和完整付费资源包独立维护。

完整的 567 色工作流资源包可在主站获取：<https://chinesecoloratlas.com/resources>；本仓库只提供代表性样本。

你可以从 [latest release](https://github.com/chroma-cathy/chinese-color-atlas/releases/latest) 下载最新样本压缩包，也可以直接使用下面的单个文件。

| 文件 | 用途 |
|---|---|
| [Figma Community 样本](https://www.figma.com/community/file/1637863774550903181) | 可复制的 24 色 Figma Variables 入门文件，包含国潮、宋式、敦煌调色示例 |
| `docs/sample-figma-vars.json` | 小型 Figma Variables JSON 示例，用于测试变量命名和语义角色 |
| `free/cathycolor.css` | 代表性中国传统色 CSS 自定义属性样本 |
| `free/cathycolor-tailwind.cjs` | Tailwind 主题颜色 Token 样本 |
| `free/cathycolor-tokens.json` | W3C DTCG 风格设计 Token 样本 |
| `free/cathycolor-hot.swatches` | Procreate 入门色板：8 个热门颜色 |
| `free/cathycolor-verified.swatches` | Procreate 样本色板：已校验颜色 |
| `free/cathycolor-term-lichun.swatches` | Procreate 节气色板样本：立春配色 |
| `docs/sample-ai-prompts.txt` | Midjourney / SDXL 工作流的 AI 提示词小样 |
| `docs/figma-community-description.md` | 可直接复制的 Figma Community 发布文案 |

## 快速使用

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

下载 `free/` 目录中的任意 `.swatches` 文件，然后在已安装 Procreate 的 iPad 上打开。

### Figma Variables

构建 Figma Variables 集合时，可以把 `docs/sample-figma-vars.json` 当作一个小型参考。它包含 24 个代表性 primitive，以及国潮、宋式、敦煌调色模式的语义示例。

复制实时 Figma Community 样本，在 Figma 中直接测试颜色：

https://www.figma.com/community/file/1637863774550903181

这个 Figma 样本适合 UI、品牌、编辑设计、包装和文化设计探索。发布文案和说明保存在 `docs/figma-community-description.md`。

Figma 实用工作流指南：<https://chinesecoloratlas.com/guides/chinese-colors-for-figma>。

关于文化色彩 primitive、语义角色和场景模式背后的设计系统框架，请看：<https://chinesecoloratlas.com/guides/cultural-color-design-systems>。

### AI 提示词

使用 `docs/sample-ai-prompts.txt` 测试 Midjourney、SDXL 或 ComfyUI 提示词。文件包含单色提示词、负面提示词建议，以及 3 组配色方案。

## 完整资源包

完整设计资源包包含全部 567 色，以及 Adobe ASE、完整 Procreate 色板、Figma Variables、CSS、Tailwind、W3C DTCG Tokens、AI 提示词、乾隆色谱数据、敦煌配色、节气色板和完整 JSON 数据集。

- 网站：https://chinesecoloratlas.com
- 免费样本：https://chinesecoloratlas.com/resources/free
- 付费资源包：https://chinesecoloratlas.com/resources
- 方法论与数据来源：https://chinesecoloratlas.com/about

## 免费与付费边界

这个仓库有意保持小而公开，适合发现、演示、教程、署名和工作流测试。

它不包含完整的 567 色 Figma Variables 文件、完整 Adobe ASE 调色板、完整 Procreate 色板、完整 AI 提示词包、乾隆 / 敦煌研究 JSON，或完整生产交付文件。这些完整工作流文件会通过 Chinese Color Atlas 网站上的资源包交付。

## 适合谁使用

- 正在构建中国风视觉系统的 UI 和品牌设计师
- 需要 CSS / Tailwind / Token 导出的前端开发者
- 使用 Procreate 色板的插画师
- 编写中国美学提示词的 AI 图像创作者
- 需要谨慎来源标注的研究者和文化项目

典型使用场景包括产品 UI、品牌系统、编辑排版、包装研究、文化情绪板、教育资源和设计系统实验。

## 署名

Chinese Color Atlas 是 Chroma Cathay 项目。如果你在公开资源、文档、教程或衍生数据集中使用这些资产，欢迎署名。

建议署名：

> Chinese traditional color samples from Chinese Color Atlas by Chroma Cathay: https://chinesecoloratlas.com

数据来源说明见 `ATTRIBUTION.md`。

## 许可证

除来源标注另有说明外，本仓库中的代码和样本导出文件按 MIT License 发布。请参阅 `LICENSE` 和 `ATTRIBUTION.md`。
