# TannenWaddy 的個人博客

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

### 1. 使用模板新建倉庫

喺本倉庫頁面點擊 **Use this template** → **Create a new repository**：

- 部署到 `https://<用戶名>.github.io`：倉庫名必須填 `<用戶名>.github.io`，無需額外配置
- 部署到 `https://<用戶名>.github.io/<倉庫名>`：倉庫名任意，同時需喺 `vite.config.ts` 嘅 `defineConfig` 中添加 `base: '/<倉庫名>/'`

模板生成嘅係全新倉庫，只有一個初始提交，唔含本倉庫嘅歷史。

### 2. 克隆到本地

```bash
git clone https://github.com/<用戶名>/<倉庫名>.git
cd <倉庫名>
```

clone 會自動配置好遠程倉庫 `origin`，可直接提交推送。

### 3. 安裝依賴並開發

```bash
pnpm i
pnpm approve-builds
pnpm dev
```

瀏覽器打開終端提示嘅地址即可預覽，修改代碼自動熱更新。

### 4. 部署到 GitHub Pages

喺倉庫 **Settings** → **Pages** → **Source** 選擇 **GitHub Actions**。此後每次推送到 `main` 分支都會自動構建並發布。
