TravelSplit V2.4 PWA 使用說明

1. 舊版先到「備份與匯出」匯出 JSON，確認檔案確實儲存。
2. 將本資料夾所有檔案及 icons 資料夾部署至同一個 HTTPS 網址（例如 GitHub Pages）。
3. 用手機瀏覽器開啟網址；Android Chrome 可選「安裝應用程式」；iPhone Safari 選「加入主畫面」。
4. 安裝後，在「備份與匯出」匯入舊 JSON，確認帳目與金額。
5. 首次載入需網路；完成快取後可離線使用核心功能。
6. JSON 仍須定期手動備份。網站資料清除或移除 App 可能導致資料遺失。
7. 本機雙擊 index.html 仍可用於舊式離線操作，但無法啟用正式 PWA Service Worker。
8. GitHub Pages 的檔案是公開的，切勿上傳含個人帳目的 JSON。
9. 發布新版時應更新 sw.js 的 CACHE 版本字串，以確保快取刷新。
