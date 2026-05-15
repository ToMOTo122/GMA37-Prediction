# 🏆 第37屆金曲獎 - 我的專屬預測排名 (GMA 37 Predictions)

這是一個專為華語音樂愛好者打造的互動式網頁工具。使用者可以透過簡單的「拖曳」方式，為第37屆金曲獎（GMA 37）各大獎項的入圍者進行個人心目中的排名預測，並一鍵匯出成精美的圖片與朋友分享！

👉 **[點我立即體驗預測 (Live Demo)](gma37-myfavourite.netlify.app)**

## ✨ 核心功能 (Features)

*   **🖱️ 拖曳排序 (Drag & Drop)**：使用 Sortable.js 打造流暢的拖曳體驗。
*   **👁️ 懸停詳細資訊 (Hover Info)**：滑鼠移至專輯封面，會自動顯示蒙版與完整的入圍者/專輯名稱。
*   **📸 一鍵匯出長圖 (Export to Image)**：內建 html2canvas，可將你的預測清單直接截圖下載。
*   **⚙️ 自訂匯出設定**：可自由勾選想要匯出哪些獎項，以及是否要在圖片上加上 1, 2, 3 等排名數字蒙版。
*   **📱 響應式設計 (RWD)**：支援手機與電腦版瀏覽。

## 🛠️ 技術棧 (Tech Stack)

*   **HTML5 / CSS3 / JavaScript (Vanilla)**
*   **Tailwind CSS** 
*   [**Sortable.js**](https://sortablejs.github.io/Sortable/) 
*   [**html2canvas**](https://html2canvas.hertzen.com/) 


## 🚀 本地執行 (Local Setup)

由於圖片和 html2canvas 匯出可能涉及 CORS（跨來源資源共用）問題，建議不要直接雙擊 `index.html` 開啟。
請使用本地伺服器運行，例如：

* **VS Code**: 安裝並使用 `Live Server` 擴充套件。
* **Python**: 在終端機輸入 `python -m http.server`。
* **Node.js**: 在終端機輸入 `npx serve`。

## 📁 檔案結構說明

* `index.html`: 主程式碼（包含 UI 結構與所有邏輯）。
* `cover/`: 存放所有入圍者專輯封面的資料夾。命名規則為 `{獎項ID}-{入圍者順序}.jpg` (例如 `1-1.jpg`)。

## ⚠️ 免責聲明

本專案僅為技術交流與個人娛樂分享之用。專案內出現之獎項名稱、歌手姓名、音樂作品名稱及專輯封面圖片，其版權均屬於「文化部影視及流行音樂產業局」、相關唱片公司及原創作者所有。本網站不具備任何商業營利用途。
