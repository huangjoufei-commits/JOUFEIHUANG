# 黃柔翡 Jou Fei Huang — 個人網站

用純 HTML/CSS 製作的個人學術網站，可透過 GitHub Pages 免費架設。

## 檔案結構
```
.
├── index.html          # About 頁面（首頁）
├── publications.html   # Publication 頁面
├── assets/
│   ├── style.css
│   └── cv2026_huang.pdf   # ← 請把你的 CV 放進這裡
└── README.md
```

## 如何用 GitHub Pages 上架（完全免費）

1. 到 https://github.com 註冊帳號（如果還沒有的話）
2. 建立一個新的 Repository
   - Repository name 建議取：`你的帳號名稱.github.io`（例如 `joufeihuang.github.io`），這樣網址會最簡潔
   - 設為 Public
3. 把這個資料夾裡的所有檔案上傳到這個 repository
   - 網頁版：進入 repo 頁面 → Add file → Upload files → 把檔案拖進去 → Commit
   - 或用 git 指令（如果你熟悉的話）：
     ```
     git init
     git add .
     git commit -m "first version"
     git branch -M main
     git remote add origin https://github.com/你的帳號/你的帳號.github.io.git
     git push -u origin main
     ```
4. 到 repo 的 Settings → Pages
   - Source 選擇 `Deploy from a branch`
   - Branch 選 `main`，資料夾選 `/ (root)` → Save
5. 等 1–2 分鐘，網站就會上線，網址是：
   `https://你的帳號.github.io/`
   （如果 repo 名稱不是 `帳號.github.io`，網址會是 `https://你的帳號.github.io/repo名稱/`）

## 內容更新
- CV、期刊 DOI 連結、outreach article 連結已全部補上
- 之後有新的論文、研討會發表或 CV 更新，把 `index.html` / `publications.html` 對應段落複製格式修改即可，或直接告訴我，我幫你更新
