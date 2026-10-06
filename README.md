# 培養照片週報（可安裝版 App）

## 檔案說明
- `index.html`：App 本體
- `manifest.webmanifest`：App 名稱、圖示等安裝設定
- `sw.js`：離線功能（沒網路也能開）
- `icons/`：App 圖示

## 第一步：放上 GitHub Pages（免費，只需做一次）
1. 到 https://github.com 註冊帳號並登入。
2. 右上角「+」→「New repository」，名稱輸入 `photo-report`，選 **Public**，按「Create repository」。
3. 在新頁面點「uploading an existing file」，把**解壓縮後資料夾裡的所有檔案和 icons 資料夾**拖進去（不是拖整個資料夾本身），按「Commit changes」。
4. 進入「Settings」→ 左側「Pages」→ Branch 選 `main`、資料夾選 `/ (root)` → 「Save」。
5. 等 1～2 分鐘，網址會是：`https://你的帳號.github.io/photo-report/`

## 第二步：安裝
**Android 手機**：用 Chrome 開啟上面的網址 →按 App 右上角「安裝 App」，或 Chrome 選單「⋮」→「安裝應用程式」。
**Windows 電腦**：用 Edge 或 Chrome 開啟網址 →按 App 右上角「安裝 App」，或網址列右側的安裝圖示。

## 重要：資料存放
- 照片只存在各自裝置的 App 裡，手機和電腦**不會自動同步**。
- 要在電腦做報表：手機上按「匯出備份」→ 把備份檔傳到電腦（LINE、雲端硬碟、USB）→ 電腦 App 按「匯入備份」。重複匯入不會產生重複照片。
- 解除安裝 App 或清除 Chrome 網站資料會刪除照片，請定期匯出備份。

## 之後修改程式
把新的 `index.html` 上傳覆蓋，並把 `sw.js` 第一行附近的 `culture-weekly-v1` 改成 `v2`，App 下次開啟就會更新。
