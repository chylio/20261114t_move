# T-MOVE 網站部署說明（GitHub Pages）

## 檔案
- `index.html`：網站本體
- `img/`：四位顧問的介紹卡
- `video/`：宣傳影片 `tmove-promo.mp4`（約 9.8MB）與封面 `poster.jpg`

請保持這三樣的資料夾結構，一起上傳。

## 上傳步驟
1. 在 GitHub 建立新的公開 repository，例如 `tmove`。
2. 「Add file → Upload files」，把 `index.html`、`img` 和 `video` 兩個資料夾一起拖進去，按 Commit changes。
   （GitHub 網頁上傳單檔上限 25MB，壓縮後的影片在範圍內。）
3. 「Settings → Pages」，Source 選 `Deploy from a branch`，Branch 選 `main`、資料夾 `/ (root)`，按 Save。
4. 約 1 分鐘後網址為 `https://你的帳號.github.io/tmove/`。

## 換影片
用同樣的檔名 `video/tmove-promo.mp4` 覆蓋上傳即可，網頁不用改。
