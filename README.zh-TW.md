# TannenWaddy 的個人部落格

> 本網站剛剛開始搭建，尚未開發完成，敬請期待。
>
> 本文件由 Kimi K3 模型翻譯，如發現翻譯不準確，歡迎提交 PR 告訴我正確的翻譯。

![License](https://img.shields.io/github/license/TannenWaddy/TannenWaddy.github.io?color=blue&style=for-the-badge)
![pnpm](https://img.shields.io/badge/pnpm-v11.15-F69220?style=for-the-badge&logo=pnpm&logoColor=white)
![SolidJS](https://img.shields.io/badge/SolidJS-v1.9-2C4F7C?style=for-the-badge&logo=solid&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-v7.0-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-v7.1-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![UnoCSS](https://img.shields.io/badge/UnoCSS-v66.5-333333?style=for-the-badge&logo=unocss&logoColor=white)
[![Edit in WebStorm](https://img.shields.io/badge/Edit_in-WebStorm-000000?style=for-the-badge&logo=webstorm&logoColor=white)](https://www.jetbrains.com/webstorm/)

## 本地開發

### 1. 使用範本新建儲存庫

在本儲存庫頁面點擊 **Use this template** → **Create a new repository**：

- 部署到 `https://<使用者名稱>.github.io`：儲存庫名稱必須填 `<使用者名稱>.github.io`，無需額外設定
- 部署到 `https://<使用者名稱>.github.io/<儲存庫名稱>`：儲存庫名稱任意，同時需在 `vite.config.ts` 的 `defineConfig` 中新增 `base: '/<儲存庫名稱>/'`

範本產生的是全新儲存庫，只有一個初始提交，不含本儲存庫的歷史紀錄。

### 2. 複製到本地

```bash
git clone https://github.com/<使用者名稱>/<儲存庫名稱>.git
cd <儲存庫名稱>
```

clone 會自動設定好遠端儲存庫 `origin`，可直接提交推送。

### 3. 安裝相依套件並開發

```bash
pnpm i
pnpm approve-builds
pnpm dev
```

瀏覽器開啟終端機提示的網址即可預覽，修改程式碼自動熱更新。

### 4. 部署到 GitHub Pages

在儲存庫 **Settings** → **Pages** → **Source** 選擇 **GitHub Actions**。此後每次推送到 `main` 分支都會自動建置並發布。
