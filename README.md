# 旻言教室

這個公開專案只包含「旻言教室」的輕量 GitHub Pages 靜態入口。

開啟網站後，瀏覽器會立即前往現有正式 Apps Script 網址；如瀏覽器未能自動跳轉，可按「開始學習」。入口不載入外部字型、程式庫或圖片，也不儲存登入資料、不呼叫 API、不預取題目。

## 正式課室

[進入旻言教室](https://script.google.com/macros/s/AKfycbycEOpljFFFdHSKUlsHuFz_qptY2z9zsqRDft0NAaBa5xLyCPAe-QaPs3Ib4w_XhMbo/exec)

學生只需填寫班別及班號即可登入，毋須密碼或教師確認。基本版和進階版均保留朗讀、大字、提示、專注底線與休息功能。

## 程式及資料的位置

- 最新完整應用程式為 4.6.0，保存在私人 `Tank/sen-chinese-app` 專案資料夾。
- 正式應用程式及後端繼續由 Google Apps Script 運行；現有正式網址不變。
- 完整題庫、答案及學生紀錄保持私人，沒有放在這個公開專案。

GitHub Pages 提供靜態入口，不會執行 Apps Script 後端。後續更新現有 Apps Script 部署時，這個入口會繼續指向同一正式網址。

## 發布設定

在 repository 的 **Settings → Pages** 選擇 **Deploy from a branch → main → / (root)**。公開專案只需這三個檔案：

- `index.html`
- `README.md`
- `.nojekyll`

在網址後加上 `?stay=1` 可預覽入口頁面，暫停自動跳轉。這個參數只影響入口，不會傳至 Apps Script。
