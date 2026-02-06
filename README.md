# 🏗️ 結構與土木工程網頁工具箱 (Web Tools for Civil Engineers)

[![HTML5](https://img.shields.io/badge/HTML-5-orange.svg)]()
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow.svg)]()
[![Engineering](https://img.shields.io/badge/Civil-Engineering-blue.svg)]()

> 集合圖檔檢視、結構模型檢查與輔助計算的輕量化網頁工具。
> 所有的運算皆在瀏覽器本地端執行，**檔案不會上傳至伺服器，確保資料安全**。

---

## 👨‍💻 專案簡介

在工程實務中，我們常需要在沒有安裝專業軟體（如 AutoCAD, ETABS）的電腦上快速查看圖檔或模型數據。為了提升工作效率，我開發了這套基於 Web 技術的工具集。

**特色：**
*   🚀 **免安裝**：單一 HTML 檔案，點開即用。
*   🔒 **隱私安全**：純前端運算，您的 DXF 或 E2K 檔案不會傳送到網路上。
*   📱 **跨平台**：支援 Windows, Mac, 甚至平板操作。

---

## 🛠️ 工具列表與功能 (Tools)

### 1. 🚜 DXF 圖檔檢視與土方計算
*   **檔案名稱**：`dxf-viewer-土方計算-v12-0.html`
*   **功能**：
    *   免開 CAD 即可在瀏覽器預覽 `.dxf` 格式圖檔。
    *   內建土方網格算法，可根據高程點進行簡易的挖填方體積估算。
    *   支援圖層開關與縮放平移。

### 2. 🏢 ETABS E2K 結構模型檢視器
*   **檔案名稱**：`etabs-v9-E2K結構模型檢視器.html`
*   **功能**：
    *   解析 ETABS 輸出的 `.e2k` 文字檔。
    *   將文字數據轉化為 3D 線架構模型，快速檢查桿件連結與節點座標。
    *   解決現場無 ETABS 授權時，無法確認模型幾何資訊的困擾。

### 3. 🔐 Excel VBA 專案密碼救援
*   **檔案名稱**：`VBA密碼破解器.html`
*   **功能**：
    *   針對忘記密碼的 Excel VBA 專案 (Macro) 進行解鎖或重置。
    *   *注意：本工具僅限於救援使用者自身擁有的檔案，請勿用於非法用途。*

---

## 🚀 如何使用 (Usage)

### 方式一：直接下載 (推薦離線使用)
1. 點擊右上角的綠色按鈕 **<> Code**。
2. 選擇 **Download ZIP**。
3. 解壓縮後，直接雙擊 `.html` 檔案即可用瀏覽器 (Chrome/Edge) 開啟。

### 方式二：GitHub Pages 線上執行
*(如果你有設定 GitHub Pages，請將連結貼在這裡，例如：)*
*   [點此開啟工具列表](https://yunen1007.github.io/web/)

---

## ⚠️ 免責聲明 (Disclaimer)

1.  **工程安全性**：本倉庫提供的土方計算與模型檢視功能僅供**輔助參考**與**初步檢核**。正式的結構簽證與計價數量，請務必以專業授權軟體（如 AutoCAD Civil 3D, CSI ETABS）之運算結果為準。
2.  **使用授權**：VBA 工具僅供找回遺失密碼之正當用途，作者不鼓勵亦不對任何侵權行為負責。

---

## 📬 關於作者

**Yunen1007**
*   專注於將 Web 技術應用於土木結構領域。
*   如有 Bug 回報或功能建議，歡迎提交 Issue。
