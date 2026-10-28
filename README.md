# BTC 網格體檢台

派網 BTC 做多網格（合約／現貨）的打分與試算，做成可以加到手機主畫面的 App（PWA）。

- 頁面、計算引擎與你輸入的參數都存在裝置上：打開即用，離線也能算。
- 市場數據與「請 Claude 解釋」透過你自己的 Google Apps Script（`Code.gs` 的 `doPost`）取得；
  打開時先用裝置裡的上一份市場數據，背景再同步最新的；離線時按的「更新／解釋」會在連線後自動送出。
- 這個儲存庫只放前端（`index.html`、`sw.js`、`manifest.webmanifest`、圖示）。
  Apps Script 網址與通行碼只存在使用者的裝置上，不在這裡。
