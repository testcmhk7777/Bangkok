# 曼谷漫遊網頁版

「曼谷漫遊」是一個可直接透過瀏覽器開啟的五日旅行行程網站。網站提供日期切換、景點詳情、Google Maps 搜尋入口與網址分享功能；不需要帳號、安裝或後端資料庫。

## 發布方式

推送至 `main` 分支後，GitHub Actions 會自動將本網站部署至 GitHub Pages。發布設定位於 `.github/workflows/deploy-pages.yml`，而網站內容由根目錄的 `index.html` 提供。
