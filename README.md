# 看見畢氏定理

用三個互動動畫證明畢氏定理 a² + b² = c²。

| 頁面 | 檔案 | 內容 |
|---|---|---|
| 首頁 | `index.html` | 定理介紹、名稱由來、勾股數表、斜邊計算機 |
| 證明一 | `water.html` | 倒水實驗：兩股正方形的水剛好裝滿斜邊正方形 |
| 證明二 | `liuhui.html` | 劉徽青朱出入圖：出入相補，合成弦方 |
| 證明三 | `rearrange.html` | 大正方形重拼：(a+b)² 的兩種拼法 |

所有頁面都是純 HTML + CSS + JavaScript，不需要安裝或編譯。字型從 Google Fonts 載入，離線時會改用系統字型。

## 放上 GitHub Pages

1. 在 GitHub 建立一個新的 repository（例如 `pythagoras`），設為 Public。
2. 點 **Add file → Upload files**，把這個資料夾裡的所有檔案（包含 `.nojekyll`）拖進去，按 **Commit changes**。
3. 到 **Settings → Pages**，Source 選 **Deploy from a branch**，Branch 選 `main`、資料夾選 `/ (root)`，按 **Save**。
4. 等一兩分鐘，網址會是 `https://你的帳號.github.io/pythagoras/`。

## 在自己電腦上看

直接用瀏覽器打開 `index.html` 就可以。
