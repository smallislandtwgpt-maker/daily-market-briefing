# 每日國際金融投資晨報

這是一個靜態 HTML 晨報網站，可部署到 GitHub Pages 或 Netlify。

## 檔案結構

- `index.html`：公開網站首頁，連到最新晨報。
- `daily-briefings/`：每日 HTML 晨報與列表頁。
- `netlify.toml`：Netlify 靜態網站部署設定。

## GitHub Pages

1. 建立一個 GitHub repository。
2. 將本資料夾內容 push 到 repository。
3. 到 repository 的 Settings → Pages。
4. Source 選擇 `Deploy from a branch`。
5. Branch 選擇 `main`，folder 選擇 `/root`。

## Netlify

1. 到 Netlify 建立新專案。
2. 連接 GitHub repository 或直接拖曳整個資料夾部署。
3. Publish directory 使用 `.`。
4. 不需要 build command。

