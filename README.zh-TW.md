<h1 align="center">All-Good-UI</h1>

<p align="center">
  <strong>Miranda — 一位毒舌的 UI 專家技能包，專為 Claude Code 設計。</strong><br>
  她能看穿每一個瑕疵、親手修好，確保你的 UI 達到上線水準。<br>
  只有 <code>.md</code> 檔案，你真的讀得懂。
</p>

<p align="center">
  <img src="https://img.shields.io/badge/license-MIT-D4A5A5?style=flat-square" alt="MIT License">
  <img src="https://img.shields.io/badge/claude_code-skill-B8A9C9?style=flat-square" alt="Claude Code Skill">
  <img src="https://img.shields.io/badge/dependencies-zero-A8B5A0?style=flat-square" alt="Zero Dependencies">
  <img src="https://img.shields.io/badge/files-13%20docs-E8B4B8?style=flat-square" alt="13 Documents">
</p>

<p align="center">
  <a href="README.md">English</a> &nbsp;|&nbsp; <b>繁體中文</b> &nbsp;|&nbsp; <a href="README.ja.md">日本語</a>
</p>

---

## 問題在哪

- AI 產出的 UI 一看就是 AI 做的 —— 完美對稱、萬年卡片、安全配色、毫無個性
- 設計規則都在你腦袋裡，不在系統裡 —— 每做一頁都像丟硬幣
- 無障礙、SEO、響應式、動畫效能 —— 每次都要手動檢查太多東西
- 你上線了，才發現手機上對比度壞了、按鈕根本沒有 focus 外框

---

## 解決方案

All-Good-UI 會為你安裝 **Miranda**，一位品味無可挑剔、對平庸零容忍的資深 UI 專家。她帶領五位專業子代理，同步作業。

### :busts_in_silhouette: 團隊成員

| 名字 | 角色 | 負責什麼 |
| :--- | :--- | :------- |
| **Miranda** | Creative Director（創意總監） | 帶領團隊、訪談使用者、做設計決策、整合成果 |
| **Emily**（艾蜜莉） | Visual Lead（視覺總管） | 字體排版、色彩系統、間距、視覺層次、深色模式 |
| **Serena**（瑟琳娜） | Art Director（美術總監） | 圖示、動畫、轉場、微互動、裝飾元件 |
| **Victor**（維克多） | Senior Auditor（品質督察） | 品質稽核、AI 痕跡偵測、反模式掃描、最後打磨 |
| **Jocelyn**（喬瑟琳） | Layout Engineer（排版工程師） | 響應式設計、格線系統、無障礙、鍵盤導覽 |
| **Andy**（安迪） | SEO & Deploy（上線專員） | SEO / AIO / GEO / SGE 中繼資料、結構化資料、Core Web Vitals、部署前檢查 |

### :sparkles: Miranda 能做什麼

| 能力 | 說明 |
| :--- | :--- |
| 從零打造 | 訪談、產出設計系統、完整頁面建構 |
| 重新設計既有頁面 | 診斷問題、修復、稽核結果 |
| 多版本比較 | 產出 3-5 個設計方向，讓你自由混搭 |
| 自動品質檢查 | 無障礙、AI 痕跡、效能、響應式、SEO —— 每次建構後自動跑 |
| 嚴重分級處理 | 嚴重問題自動修、偏好問題報告給你決定 |
| 可直接上線 | 程式碼直接部署，SEO、無障礙、效能都處理好了 |

---

## :package: 安裝方式

**第 1 步** —— Clone 或複製到你的 Claude Code 技能目錄：

```bash
git clone https://github.com/HelloRuru/ALL-GOOD-UI.git ~/.claude/skills/all-good-ui
```

**第 2 步** —— 完成。Miranda 會在你開啟對話時自動啟動。

**第 3 步（選用）** —— 安裝 Better Icons MCP，取得 200,000+ 圖示搜尋：

<details>
<summary><strong>點擊展開</strong></summary>

加入 `~/.claude/settings.json`：

```json
{
  "mcpServers": {
    "better-icons": {
      "command": "npx",
      "args": ["-y", "better-icons"]
    }
  }
}
```

</details>

---

## :brain: Miranda 怎麼運作

Miranda 自動啟動，依照結構化流程執行：

**階段 0：偵測** —— 掃描你的專案，辨識框架、套件管理器、樣式系統、既有設計 token。

**階段 1：訪談** —— 先問你偏好的語言（英文或中文），再問你想要多詳細的訪談。快速模式（3-5 題）或完整模式（8-12 題）。

**階段 2：建構** —— 派出團隊同步作業。Emily 負責視覺、Serena 負責動態、Jocelyn 負責版面、Andy 負責 SEO。同時進行，不是排隊等。

**階段 3：自動稽核** —— Victor 自動跑完整品質檢查，涵蓋無障礙、AI 痕跡偵測、動畫效能、響應式表現、SEO 完整度。

**階段 4：修復** —— 嚴重問題立刻修。字體大小偏好之類的主觀微調會報告給你決定。

**階段 5：交付** —— 可直接上線的程式碼。

---

## :shield: 兩種模式

| 模式 | 適用時機 | 行為 |
| :--- | :------- | :--- |
| **主導模式（Boss Mode）** | 沒有既有設計系統，或你想讓 Miranda 主導 | Miranda 做所有設計決策。有衝突時她的標準優先。 |
| **顧問模式（Consultant Mode）** | 你有自己的品牌 / 設計系統 | Miranda 尊重你的限制，但遇到客觀壞掉的東西（對比度、無障礙、效能）還是會標出來。 |

---

## :open_file_folder: 檔案結構

```
all-good-ui/
  SKILL.md                        # 主入口 —— 角色、流程、團隊、指令
  reference/
    typography.md                  # 字體堆疊、字級、行高、載入策略
    color.md                       # 色彩系統、對比度、深色模式、色彩科學
    spacing.md                     # 4pt 格線、間距級距、視覺節奏
    motion.md                      # 動畫時序、緩動函數、效能、彈簧動畫
    interaction.md                 # 8 種狀態、表單、焦點、載入、錯誤
    responsive.md                  # 行動優先、斷點、容器查詢
    accessibility.md               # WCAG AA、ARIA、鍵盤、焦點管理
    metadata-seo.md                # SEO / AIO / GEO / SGE、結構化資料、OG
    anti-patterns.md               # AI 痕跡清單、設計反模式
  workflow/
    audit.md                       # 完整品質稽核流程（18 類別）
    design-lab.md                  # 多版本產出與比較
    icons.md                       # 圖示選用 + Better Icons MCP 整合
```

---

## :speech_balloon: 指令

| English | 中文 | 功能說明 |
| :------ | :--- | :------- |
| "Check this" / 「檢查一下」 | "Checking" / 「檢查中」 | Victor 跑完整稽核 |
| "Build a page" / 「幫我建一頁」 | "Building" / 「建構中」 | 從階段 1 開始的完整建構流程 |
| "Fix this" / 「修一下」 | "Fix this" / 「修一下」 | Miranda 診斷並修復 |
| "Show me options" / 「給我看版本」 | "Show versions" / 「秀版本」 | 產出 3-5 個變體讓你比較 |
| "Be the boss" / 「你來主導」 | "You lead" / 「你帶」 | 切換到主導模式 |
| "Just advise" / 「給建議就好」 | "Just advise" / 「給建議就好」 | 切換到顧問模式 |
| "Deploy check" / 「部署前檢查」 | "Pre-deploy check" / 「上線前檢查」 | Andy 跑部署前稽核 |
| "Too much AI" / 「太像 AI 了」 | "Too much AI" / 「太像 AI 了」 | Victor 掃描 AI 痕跡 |

---

## :wrench: 客製化

| 想改什麼 | 去哪改 |
| :------- | :----- |
| Miranda 的個性 | `SKILL.md` > Persona 區塊 |
| 團隊成員 | `SKILL.md` > The Team 區塊 |
| 字體排版規則 | `reference/typography.md` |
| 色彩系統 | `reference/color.md` |
| 什麼算「嚴重」 | `SKILL.md` > Phase 4: Severity-Based Action |
| 稽核清單 | `workflow/audit.md` |
| 圖示偏好 | `workflow/icons.md` |

---

## :bulb: 設計哲學

**為什麼用角色，不只是列規則？**
文件裡的規則會被跳過。一個有觀點的角色才真的會被遵守。Miranda 不只列出哪裡有問題 —— 她帶著態度直接修好。這讓產出更有記憶點、更一致。

**為什麼用子代理？**
設計同時涉及多個領域 —— 色彩、版面、無障礙、SEO。透過專業代理同步處理，比單一流程跑過一遍更快、更完整。

**為什麼要偵測「AI 痕跡」？**
AI 產出的 UI 最大破綻就是看起來像 AI 做的。完美對稱、千篇一律的三欄卡片、安全的藍灰色調。Miranda 的團隊專門偵測這些模式，然後打破它們。

---

## :pray: 靈感來源與致謝

> **所有內容皆為原創撰寫。** 沒有複製任何原始碼。Miranda 的設計知識是從以下專案所教授的原則中歸納而成。

| 專案 | 啟發的概念 | 連結 |
| :--- | :--------- | :--- |
| Impeccable | 設計科學、反模式、7 領域參考系統 | [Website](https://impeccable.style/) |
| Taste Skill | 美學標準、AI 痕跡偵測、風格預設 | [GitHub](https://github.com/Leonxlnx/taste-skill) |
| Superdesign | 自動偵測、變體產出、設計系統骨架 | [Website](https://app.superdesign.dev/) |
| UI Skills | 基準 UI、無障礙、中繼資料、動畫效能 | [Website](https://www.ui-skills.com/) |
| Better Icons | 200k+ 圖示搜尋（透過 MCP） | [GitHub](https://github.com/better-auth/better-icons) |
| Design Plugin | 多版本比較、回饋蒐集流程 | [GitHub](https://github.com/0xdesign/design-plugin) |

---

## 系統需求

- [Claude Code](https://claude.ai/claude-code)（CLI 或 VS Code 擴充功能）
- Node.js 18+（僅在使用 Better Icons MCP 時需要）

## 授權

MIT —— 詳見 [LICENSE](LICENSE)。

---

<p align="center">
  Made by <a href="https://ohruru.com">HelloRuru</a> -- because good UI shouldn't need an explanation.
</p>
