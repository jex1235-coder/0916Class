# 0916Class - AIOT 數據分析

> 📚 **課程名稱**：AIOT 數據分析  
> 👤 **作者 / 開發者**：白育誠 (Yu-Cheng Bai)  
> 💼 **專業職稱**：Embedded & Software Engineer  
> 🌐 **LIVE DEMO 網站**：[https://jex1235-coder.github.io/0916Class/](https://jex1235-coder.github.io/0916Class/)  
> 📦 **GitHub 儲存庫**：[https://github.com/jex1235-coder/0916Class](https://github.com/jex1235-coder/0916Class)  

---

## 🌟 LIVE DEMO 線上體驗

👉 **點擊前往線上展示網站：[LIVE DEMO - 白育誠 個人儀表板與技能樹](https://jex1235-coder.github.io/0916Class/)**

---

## 📖 專案簡介 (About The Project)

本專案為 **AIOT 數據分析** 課程成果展示網站，以知名開發者路線圖網站 [roadmap.sh](https://roadmap.sh) 的現代 UI/UX 風格為基礎，打造專屬於 **Embedded & Software Engineer** 的個人化技術路線圖與即時系統監控儀表板。

網站核心包含**即時跳動數位時鐘**、**時區顯示 (UTC+8)**、**今日時間進度條**、**年度進度條**，以及四個階段的嵌入式與軟體工程技能樹節點，並支援即時點擊側邊抽屜（Slide-over Drawer）檢視技能重點與官方學習資源。

---

## ✨ 核心功能特色 (Key Features)

### 1. 🎛️ Roadmap.sh 風格深色儀表板
- 沉浸式暗黑畫布（`#080c14` / `#0f172a`），搭配標誌性的點狀網格背景（Dotted Grid）。
- 頂部導覽列提供品牌標識、麵包屑導航（`Personal / Embedded & Software`）與系統在線綠燈狀態。

### 2. ⏱️ 即時時鐘與進度條小工具 (Live Timepiece Widget)
- **毫秒級跳動時鐘**：以大字型即時呈現當前時間 `HH:MM:SS`，支援 12H / 24H 快速切換。
- **當地日期與時區**：自動格式化顯示完整年月日與星期，標示 `UTC+8 (Taipei)`。
- **今日時間進度條 (Day Progress)**：動態計算今日 24 小時內已度過的百分比。
- **年度進度條 (Year Progress)**：即時追蹤本年度已過天數之百分比。

### 3. 👤 個人資訊與即時儲存 (Identity & Inline Edit)
- 預設顯示：**白育誠**（`Embedded & Software Engineer`）。
- 支援右上角點擊「編輯資料」，可直接修改姓名、職稱、狀態標籤與個人自介。
- **瀏覽器本機快取**：修改後的內容自動保存至 `localStorage`，重新整理不遺失。

### 4. 🗺️ 嵌入式工程師技能路線圖 (Embedded Skills Roadmap)
- **Phase 01 基礎核心 (Foundations)**：`C / C++ (C99 / C++17)`、`Data Structures & Algorithms`、`Linux & Git VCS`
- **Phase 02 嵌入式核心 (Embedded Core)**：`ARM Cortex-M Architecture`、`FreeRTOS & Multitasking`、`Bus Protocols (UART/SPI/I2C/CAN)`
- **Phase 03 進階韌體與通訊 (Advanced Firmware & IoT)**：`Firmware Architecture & HAL`、`Wireless & IoT (BLE/Wi-Fi/MQTT)`、`Embedded Linux & Yocto`
- **Phase 04 前瞻技術探索 (Next Frontier)**：`TinyML / Edge AI Inference`、`Rust for Embedded Systems`
- **側邊滑出抽屜 (Slide-over Drawer)**：點擊任一節點可展開詳細學習大綱，並可自訂切換該節點掌握狀態（已掌握 / 進行中 / 規劃中）。

### 5. ⚡ 零建置依賴 (Zero-Build)
- 單一獨立檔案架構，採用 Tailwind CSS (CDN) 與 Lucide Icons。
- 無需 Node.js 或建置打包工具，可隨時雙擊開啟用瀏覽器瀏覽，亦完美支援 GitHub Pages 靜態代管。

---

## 🚀 本地快速啟動 (Local Quick Start)

直接以瀏覽器開啟 [`index.html`](index.html)，或使用 Python 啟動輕量本地伺服器：

```bash
# 切換至專案目錄
cd D:\HomeWork

# 透過 Python 啟動 HTTP 伺服器
python -m http.server 8000
```

開啟瀏覽器並造訪 `http://localhost:8000` 即可預覽。

---

## 📄 版權與授權 (License)

由 **白育誠 (Yu-Cheng Bai)** 於 **AIOT 數據分析** 課程期間設計與實作。  
UI/UX 設計概念靈感源自 [roadmap.sh](https://roadmap.sh)。
