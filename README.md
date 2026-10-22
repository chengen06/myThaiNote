# myThaiNote

曼谷 8 天 7 夜的離線旅遊手冊（PWA）。資料只存在手機本機（localStorage），不會上傳。

## 1. 放上 GitHub Pages（約 5 分鐘）
1. 登入 GitHub → 右上角 ＋ → New repository → 名稱 `myThaiNote`，選 **Public** → Create
2. 在 repo 頁面點 **uploading an existing file**，把這 5 個檔案拖進去：
   `index.html`、`manifest.webmanifest`、`sw.js`、`icon-180.png`、`icon-512.png`（README 可以不傳）→ Commit changes
3. Settings → Pages → Branch 選 `main`、資料夾 `/ (root)` → Save
4. 等 1～2 分鐘，網址會是 `https://<你的帳號>.github.io/myThaiNote/`

> 網址是公開的。內建資料已經拿掉姓名、Email、手機號碼；你在 App 裡填的內容只存在自己手機上。

## 2. 裝到 iPhone
1. 用 **Safari** 開上面的網址（其他瀏覽器不能加入主畫面）
2. 分享按鈕 → **加入主畫面** → 加入
3. 從主畫面的「曼谷」圖示打開一次，之後就可以離線使用

## 3. 使用
- 每頁右上 ✎：編輯標題、項目、筆記，⇥ 調整縮排，✕ 刪除項目，🗑 刪除卡片，底部可新增卡片
- 卡片右上 ⋮⋮：按住上下拖曳，調整順序
- 行李頁「去程／回程」各自記錄勾選狀態
- 記帳：THB 或 TWD 都可以記，匯率在 ⚙ 設定裡調整
- ⚙ 設定 → 匯出 JSON：定期備份（iOS 可能會清掉很久沒開的網站資料）

## 更新內容
修改檔案後，把 `sw.js` 裡的 `myThaiNote-v1` 改成 `v2` 再重新上傳。手機連網打開兩次就會更新（你的紀錄不受影響）。
