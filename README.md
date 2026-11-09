# 📱 我的網頁作品集 (My Web Portfolio)

[![GitHub License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/zh-TW/docs/Web/HTML)
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/zh-TW/docs/Web/JavaScript)

專為行動裝置設計的手機優先（Mobile-First）個人作品集網站。收錄 6 個以現代純前端技術構建的獨立 Web 專案，涵蓋休閒互動遊戲、企業資料脫敏安全工具、組織階層管理、財務報表智慧視覺化與產業情報趨勢報告。

---

## 🌟 特色亮點

- **📱 手機優先設計（Mobile-First UX）**：
  - 仿原生 App 的底部懸浮導航列（Tab Bar），隨時切換「作品目錄」與「關於我」。
  - 專為拇指操作設計的大觸控目標（48px+）與分類橫向平滑滾動。
  - 完全適配各尺寸手機（支援 Safe Area 安全區域）與桌面寬螢幕自適應排版。
- **⚡ 純前端即開即用**：所有應用皆無需任何後端伺服器或資料庫環境，以瀏覽器原生 API 與開源前端庫實作，點擊即開、資安無虞。
- **🎵 背景音樂整合**：內建背景音訊播放器（支援頂部與底部懸浮雙向連動控制）。

---

## 📂 收錄作品列表

| # | 作品名稱 | 核心技術 / API | 應用場景 | 直接體驗 |
|---|---|---|---|---|
| 01 | **水球爆爆大作戰** | HTML5 Canvas 2D API<br>Web Audio API (動態音效合成)<br>Touch & Pointer Events | 行銷活動互動遊戲、展會現場互動、觸控遊戲開發範例 | [開啟體驗](apps/water%20bomb%20battle.html) |
| 02 | **合併現金流量表智慧分析** | Chart.js 視覺化圖表庫<br>HTML5 Canvas API<br>Web Storage API | 上市櫃財報體質診斷、高階資金調度分析、個人價值投資決策 | [開啟體驗](apps/Cash%20Flow%20Statement.html) |
| 03 | **部門階層架構與人員異動管理** | PapaParse CSV 解析 API<br>DOM Tree 階層運算<br>Blob & File Download | 企業年度組織改組、HR 人力調配與審核、組織編制可視化 | [開啟體驗](apps/organization_hierarchy_manager%20.html) |
| 04 | **企業資料去識別化防護工具** | CryptoJS (SHA-256 雜湊)<br>SheetJS (XLSX/CSV 處理)<br>FileReader API (純本地運算) | 測試資料對外釋出防護、AI 模型訓練資料脫敏、個資法規遵循 | [開啟體驗](apps/data%20deidentification.html) |
| 05 | **2026 製造業導入生成式 AI 趨勢報告** | Intersection Observer API<br>CSS Scroll-Behavior<br>CSS Grid & Flexbox | 智慧製造轉型策略會議、高階顧問簡報、產業趨勢演說 | [開啟體驗](apps/industry%20intelligence.html) |
| 06 | **動漫主題大數字倒數計時器** | Web Audio API (合成警報)<br>HTML5 Fullscreen API<br>Window Timer (setInterval) | 敏捷站立會議計時、番茄鐘專注工作、活動競賽限時提醒 | [開啟體驗](apps/countdown%20timer.html) |

---

## 🗂️ 專案目錄結構

```text
myWork/
├── index.html              # 手機優先作品集首頁（作品目錄 & 關於我）
├── README.md               # 專案說明文件
├── apps/                   # 6 個獨立純前端應用專案
│   ├── water bomb battle.html
│   ├── Cash Flow Statement.html
│   ├── organization_hierarchy_manager .html
│   ├── data deidentification.html
│   ├── industry intelligence.html
│   └── countdown timer.html
├── assets/                 # 個人頭像與視覺素材
│   ├── me.png
│   ├── ai about me.png
│   └── ai about me-1.png
└── Music/                  # 背景音訊
    └── SONO FELICE.mp3
```

---

## 🚀 如何執行

1. **直接開啟**：
   - 下載或 Clone 本專案至本機後，直接以瀏覽器雙擊開啟 [`index.html`](index.html) 即可開始體驗！
2. **透過 Local Server（推薦）**：
   ```bash
   # 使用 Python 快速建立本地伺服器
   python3 -m http.server 8080
   # 接著在瀏覽器打開 http://localhost:8080
   ```
   或使用 VS Code 的 **Live Server** 擴充套件啟動。

---

## 👤 作者資訊

- **GitHub**: [@Ruby9708](https://github.com/Ruby9708)
- **專長**: 現代前端架構、互動視覺化、資安脫敏工具開發與 Mobile-First 體驗設計
