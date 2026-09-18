# BREAK ROOM 團拆控制台

新版入口為 `index.html`。GitHub Pages 設定：`main` 分支、`/ (root)`。

包含轉盤、多獎抽選、隨機分隊、骰子／擲筊規則、直播特效、OCR 與球員查詢。

`break-room-source.zip` 內含可編輯的 React / TypeScript 原始碼與鎖定依賴。解壓後執行 `npm ci` 及 `npm run build:pages`，網站輸出在 `docs/`。原始碼版本 f4703c3。

- 名單、抽選紀錄保存在目前瀏覽器，不會跨裝置同步。
- 直播外框與控制台使用同一瀏覽器，在 OBS 用「視窗擷取」。
- OCR 首次使用需下載辨識資源；辨識姓名需人工確認，球員資料查詢需連網。
- 未串接付費 AI 推薦 API，未自動擷取 YouTube 留言。
- `teambreak.html` 為保留的舊版。
