# 🌸 珍妮佛作品集 | Jennifer's Portfolio Showcase

> 精選 8 款純前端 Web 應用、3D 像素小遊戲、生產力工具與個人專業履歷展示庫。

![Portfolio Showcase](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![RWD](https://img.shields.io/badge/Responsive-RWD-blueviolet?style=for-the-badge)

---

## 📖 專案簡介

**珍妮佛作品集** 是一個以純前端技術（HTML5、Vanilla CSS3、JavaScript）打造的數位作品集入口網站。本專案收錄了 8 款各具特色的網頁作品，涵蓋 **互動遊戲**、**實用工具**、**資安脫敏**、**地圖應用** 及 **個人專業履歷**。

首頁採用現代 Glassmorphism 毛玻璃視覺設計與全響應式（RWD）排版，支援即時關鍵字搜尋、分類標籤切換、燈箱快速預覽以及深色/淺色主題模式，提供流暢且直覺的瀏覽體驗。

---

## ✨ 首頁核心特色 (`index.html`)

- 🎨 **現代高質感視覺**：結合毛玻璃質感（Glassmorphism）、微發光背景與柔和漸層，每個作品皆有專屬主題識別色。
- 📱 **全響應式設計 (RWD)**：支援手機（單欄）、平板（雙欄）及桌上型電腦（3~4 欄）最佳排版。
- 🔍 **即時搜尋引擎**：支援依作品名稱、檔案名稱、分類或技術關鍵字即時過濾，並支援快捷鍵 `/` 快速聚焦搜尋。
- 🏷️ **分類標籤篩選**：一鍵切換「全部 (8)」、「🎮 互動遊戲 (3)」、「🛠️ 實用工具 (3)」與「💼 個人作品集 (2)」。
- 👁️ **即時快速預覽**：點擊卡片上的預覽按鈕可在首頁燈箱彈窗（iframe）中直接操作工具或遊玩遊戲，無需頻繁跳轉頁面。
- 🌓 **深色 / 淺色主題切換**：內建 Dark & Light Mode，自動記住使用者的瀏覽喜好。
- ⚡ **純前端極速載入**：零外部建置工具依賴（無需 npm build），直接雙擊或透過靜態伺服器即可秒開。

---

## 📂 收錄作品目錄與功能介紹

| 檔案名稱 | 專案名稱 | 分類 | 核心技術與特色亮點 |
| :--- | :--- | :---: | :--- |
| [`game1.html`](./game1.html) | **女孩穿衣出任務 - 3D像素復古遊戲** | 🎮 互動遊戲 | • Three.js 3D Voxel 像素渲染引擎<br>• 復古 8-bit 風格換裝與場景冒險<br>• 支援多部位造型切換與互動展示 |
| [`game2.html`](./game2.html) | **小茉莉命名推薦所 🌸** | 🎮 互動遊戲 | • 日系復古可愛手繪風格與圓體字型<br>• 姓名五行、筆畫吉凶運勢靈感推薦<br>• Canvas Confetti 彩帶慶祝動畫特效 |
| [`game3.html`](./game3.html) | **復古極簡大數字倒數計時器** | ⏱️ 工具遊戲 | • 賽博龐克風格與 CRT 綠光掃描線濾鏡<br>• 超大字體倒數計時與多種警示音效<br>• 內建 Canvas 8-bit 小恐龍跑酷小遊戲 |
| [`portfolio.html`](./portfolio.html) | **Senior Marketing Executive 作品集** | 💼 個人作品集 | • 高級行銷經理人/策略總監個人履歷<br>• 整合行銷案例、社群成長與數據成效圖表<br>• 現代極簡版型與 Plus Jakarta Sans 排版 |
| [`portfolio2.html`](./portfolio2.html) | **LEE CHENG-EN (李政恩) 主廚作品集** | 💼 個人作品集 | • 當代法式料理主廚星級作品集<br>• 典雅大地色系（Taupe & Cream）與襯線字體<br>• 招牌菜品賞析、廚藝歷程與料理哲學 |
| [`tools1.html`](./tools1.html) | **餐廳訂貨申請表單系統** | 🛠️ 實用工具 | • 針對餐飲門市設計的食材與耗材採購單<br>• Alpine.js 即時品項小計與總額運算<br>• 支援 Excel (.xlsx) 匯出與列印預覽模式 |
| [`tools2.html`](./tools2.html) | **PrivaGuard Studio 個資脫敏系統** | 🛠️ 實用工具 | • 本地端純前端運行的敏感資料脫敏工具<br>• 身分證字號、手機號碼、Email 假名化<br>• 保障資安與個資合規，資料絕不上傳伺服器 |
| [`tools3.html`](./tools3.html) | **台灣衝浪浪點互動地圖** | 🗺️ 實用工具 | • Leaflet.js + OpenStreetMap 互動地圖<br>• 收錄全台灣北中南東各大衝浪熱點<br>• 浪況等級標示、季節指南與交通資訊 |

---

## 🗂️ 專案目錄結構

```text
mysite_jennifer/
├── .gitignore          # Git 忽略設定檔
├── README.md           # 專案說明文件（本檔案）
├── index.html          # 珍妮佛作品集主要首頁入口 (RWD / 搜尋 / 預覽)
├── game1.html          # 女孩穿衣出任務 (3D像素復古遊戲)
├── game2.html          # 小茉莉命名推薦所 🌸 (取名與靈感推薦)
├── game3.html          # 復古極簡大數字倒數計時器 (CRT濾鏡 / 恐龍小遊戲)
├── portfolio.html      # Senior Marketing Executive 作品集 (品牌行銷)
├── portfolio2.html     # LEE CHENG-EN 主廚法餐履歷作品集 (當代料理)
├── tools1.html         # 餐廳訂貨申請表單系統 (採購加總 / Excel匯出)
├── tools2.html         # PrivaGuard Studio 個資脫敏系統 (資安防護)
└── tools3.html         # 台灣衝浪浪點互動地圖 (全台浪點導覽)
```

---

## 🚀 如何使用與本地預覽

### 方法 1：直接開啟
直接在檔案總管中雙擊 `index.html`，即可透過預設瀏覽器瀏覽作品集。

### 方法 2：使用 Python 內建靜態伺服器（推薦）
在專案根目錄開啟終端機或命令提示字元，執行：

```bash
# 啟動本地端伺服器 (Port 8000)
python -m http.server 8000
```

接著在瀏覽器中開啟 [http://localhost:8000/index.html](http://localhost:8000/index.html) 即可體驗完整功能。

### 方法 3：使用 VS Code Live Server
若使用 VS Code，可在 `index.html` 按右鍵選擇 **「Open with Live Server」**。

---

## 🛠️ 技術棧與工具庫

- **核心架構**：Semantic HTML5, Vanilla JavaScript (ES6+), Vanilla CSS3
- **3D 與圖形繪製**：Three.js, HTML5 Canvas API
- **地圖應用**：Leaflet.js, OpenStreetMap
- **資料處理與匯出**：SheetJS (xlsx), PapaParse
- **圖示與字型**：Font Awesome 6, Google Fonts (Outfit, Noto Sans TC, Plus Jakarta Sans, Cormorant Garamond)
- **動畫特效**：Canvas Confetti, Web Audio API

---

## 📜 版本歷程

- **v1.1.0** (2026-08-18):
  - 新增完整專案說明文件 `README.md`。
- **v1.0.0** (2026-08-18):
  - 建立「珍妮佛作品集」首頁 `index.html`。
  - 完成 8 款作品收錄、檔案名稱標籤、開啟按鈕與快速預覽燈箱。
  - 支援 RWD、即時搜尋、分類篩選與深淺色主題切換。
  - 初始化 Git 本地版本控制。

---

© 2026 珍妮佛作品集 (Jennifer's Portfolio). All rights reserved.
