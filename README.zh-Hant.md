# Chinese Color Atlas - 免費樣本

[English](README.md) | [简体中文](README.zh-Hans.md)

來自 **Chinese Color Atlas** 的中國傳統色免費樣本與工作流資源。Chinese Color Atlas 是 Chroma Cathay 旗下專案。

如果你想先在真實設計和開發流程中測試中國傳統色，再決定是否使用完整色譜，可以從這個倉庫開始。這裡包含 CSS 變數樣本、Tailwind 顏色、設計 Token、Procreate 色票、AI 提示詞，以及可複製的 Figma Community 檔案。

Chinese Color Atlas 是面向設計師、開發者和創意團隊的、帶來源意識的中國傳統色參考。完整色譜覆蓋 567 個顏色；這個公開倉庫只發布具有代表性的免費樣本。

## 從這裡開始

- **設計師：** 複製 [24 色免費 Figma Variables 樣本](https://www.figma.com/community/file/1637863774550903181)。
- **開發者：** 試用 `free/cathycolor.css`、`free/cathycolor-tailwind.cjs` 或 `free/cathycolor-tokens.json`。
- **插畫師：** 匯入 `free/` 目錄中的 Procreate `.swatches` 樣本。
- **AI 圖像創作者：** 用 `docs/sample-ai-prompts.txt` 測試 Midjourney、SDXL 或 ComfyUI 工作流。
- **設計系統團隊：** 閱讀[文化色彩 Token 命名指南](https://chinesecoloratlas.com/guides/cultural-color-design-systems)。
- **需要上下文？** 閱讀免費資源頁：<https://chinesecoloratlas.com/resources/free>。

## 包含內容

這個公開倉庫只包含免費分發資產。私有產品網站和完整付費資源包獨立維護。

完整的 567 色工作流資源包可在主站取得：<https://chinesecoloratlas.com/resources>；本倉庫只提供代表性樣本。

你可以從 [latest release](https://github.com/chroma-cathy/chinese-color-atlas/releases/latest) 下載最新樣本壓縮包，也可以直接使用下面的單個檔案。

| 檔案 | 用途 |
|---|---|
| [Figma Community 樣本](https://www.figma.com/community/file/1637863774550903181) | 可複製的 24 色 Figma Variables 入門檔案，包含國潮、宋式、敦煌調色範例 |
| `docs/sample-figma-vars.json` | 小型 Figma Variables JSON 範例，用於測試變數命名和語義角色 |
| `free/cathycolor.css` | 代表性中國傳統色 CSS 自訂屬性樣本 |
| `free/cathycolor-tailwind.cjs` | Tailwind 主題顏色 Token 樣本 |
| `free/cathycolor-tokens.json` | W3C DTCG 風格設計 Token 樣本 |
| `free/cathycolor-hot.swatches` | Procreate 入門色票：8 個熱門顏色 |
| `free/cathycolor-verified.swatches` | Procreate 樣本色票：已校驗顏色 |
| `free/cathycolor-term-lichun.swatches` | Procreate 節氣色票樣本：立春配色 |
| `docs/sample-ai-prompts.txt` | Midjourney / SDXL 工作流的 AI 提示詞小樣 |
| `docs/figma-community-description.md` | 可直接複製的 Figma Community 發布文案 |

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

下載 `free/` 目錄中的任意 `.swatches` 檔案，然後在已安裝 Procreate 的 iPad 上開啟。

### Figma Variables

建立 Figma Variables 集合時，可以把 `docs/sample-figma-vars.json` 當作一個小型參考。它包含 24 個代表性 primitive，以及國潮、宋式、敦煌調色模式的語義範例。

複製即時 Figma Community 樣本，在 Figma 中直接測試顏色：

https://www.figma.com/community/file/1637863774550903181

這個 Figma 樣本適合 UI、品牌、編輯設計、包裝和文化設計探索。發布文案和說明保存在 `docs/figma-community-description.md`。

Figma 實用工作流指南：<https://chinesecoloratlas.com/guides/chinese-colors-for-figma>。

關於文化色彩 primitive、語義角色和場景模式背後的設計系統框架，請看：<https://chinesecoloratlas.com/guides/cultural-color-design-systems>。

### AI 提示詞

使用 `docs/sample-ai-prompts.txt` 測試 Midjourney、SDXL 或 ComfyUI 提示詞。檔案包含單色提示詞、負面提示詞建議，以及 3 組配色方案。

## 完整資源包

完整設計資源包包含全部 567 色，以及 Adobe ASE、完整 Procreate 色票、Figma Variables、CSS、Tailwind、W3C DTCG Tokens、AI 提示詞、乾隆色譜資料、敦煌配色、節氣色票和完整 JSON 資料集。

- 網站：https://chinesecoloratlas.com
- 免費樣本：https://chinesecoloratlas.com/resources/free
- 付費資源包：https://chinesecoloratlas.com/resources
- 方法論與資料來源：https://chinesecoloratlas.com/about

## 免費與付費邊界

這個倉庫有意保持小而公開，適合發現、演示、教學、署名和工作流測試。

它不包含完整的 567 色 Figma Variables 檔案、完整 Adobe ASE 調色盤、完整 Procreate 色票、完整 AI 提示詞包、乾隆 / 敦煌研究 JSON，或完整生產交付檔案。這些完整工作流檔案會透過 Chinese Color Atlas 網站上的資源包交付。

## 適合誰使用

- 正在建立中國風視覺系統的 UI 和品牌設計師
- 需要 CSS / Tailwind / Token 匯出的前端開發者
- 使用 Procreate 色票的插畫師
- 編寫中國美學提示詞的 AI 圖像創作者
- 需要謹慎來源標註的研究者和文化專案

典型使用場景包括產品 UI、品牌系統、編輯排版、包裝研究、文化情緒板、教育資源和設計系統實驗。

## 署名

Chinese Color Atlas 是 Chroma Cathay 專案。如果你在公開資源、文件、教學或衍生資料集中使用這些資產，歡迎署名。

建議署名：

> Chinese traditional color samples from Chinese Color Atlas by Chroma Cathay: https://chinesecoloratlas.com

資料來源說明見 `ATTRIBUTION.md`。

## 授權

除來源標註另有說明外，本倉庫中的程式碼和樣本匯出檔案按 MIT License 發布。請參閱 `LICENSE` 和 `ATTRIBUTION.md`。
