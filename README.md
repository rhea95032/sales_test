# 📊 銷售數據分析自動化報表 (Sales Data Analysis Portfolio)

[![Power BI](https://img.shields.io/badge/Tools-Power%20BI-yellow)](https://powerbi.microsoft.com/desktop/)
[![Data Source](https://img.shields.io/badge/Data-CSV-blue)](#)

## 📝 專案簡介 (Project Overview)
本專案旨在建立一個**可重複使用的數據分析模組**。透過 Power BI 的範本化設計（.pbit），使用者僅需匯入原始的銷售 CSV 檔案，即可自動生成包含銷售趨勢、產品表現及客戶分布的視覺化儀表板，大幅減少重複設定資料處理（ETL）的時間。

---

## 🛠️ 技術關鍵點 (Technical Highlights)
* **動態路徑串接**：利用 Power BI 參數化設定，讓報表具備靈活度，不需進入編輯模式即可更換資料來源。
* **ETL 流程自動化**：內建預設的資料清洗與轉換邏輯，確保 CSV 資料匯入後立即格式化。
* **互動式視覺化**：設計多維度交叉篩選器（Slicers），提供深度的數據洞察。

---

## 📂 檔案結構 (Repository Structure)

* 📦 **`Analysis_Report.pbit`**：核心報表範本，包含所有視覺化邏輯與數據模型。
* 📄 **`Sales_csv.csv`**：範例銷售數據集（包含日期、產品、金額等欄位）。
* 📖 **`README.md`**：專案說明文件。

---
## 🖼️ 報表預覽 (Dashboard Preview)

| 首頁 | 銷售 | 客群 |
| :---: | :---: | :---: |
|![Dashboard Mockup](https://github.com/rhea95032/sales_test/blob/main/img/%E9%A6%96%E9%A0%81.png)|
|![Dashboard Mockup](https://github.com/rhea95032/sales_test/blob/main/img/%E5%85%A7%E9%A0%811.png)|
|![Dashboard Mockup](https://github.com/rhea95032/sales_test/blob/main/img/%E5%85%A7%E9%A0%812.png)|
---

## 🚀 快速上手步驟 (Quick Start)

為了驗證此報表的功能，請依照以下步驟操作：

1.  **環境準備**：確保您的電腦已安裝 [Power BI Desktop](https://powerbi.microsoft.com/desktop/)。
2.  **下載專案**：複製（Clone）此倉庫或下載所有的檔案並解壓縮。
3.  **配置數據路徑** 💡：
    * 開啟 `Analysis_Report.pbit` 檔案。
    * 在跳出的 **「資料檔案路徑來源」** 視窗中，輸入您電腦中 `Sales_csv.csv` 的**完整絕對路徑**。
    * *提示：在 Windows 中對檔案按 `Shift + 右鍵` 選擇「複製為路徑」最為準確。*
4.  **生成報表**：點擊「載入」後，系統將自動完成數據對接並呈現分析畫面。

---

## 📈 預期分析產出 (Key Insights)
* **銷售趨勢**：依時間軸追蹤業績成長率。
* **產品分析**：找出貢獻度最高的前五大商品（Top 5 Products）。
* **區域表現**：透過地圖或條形圖分析不同地區的市場佔有率。

---

## 🤝 個人首頁 (Contact)
[個人首頁](https://rhea95032.github.io/)