# TannenWaddy 的个人博客


![License](https://img.shields.io/github/license/TannenWaddy/TannenWaddy.github.io?color=blue&style=for-the-badge)
![pnpm](https://img.shields.io/badge/pnpm-v11.15-F69220?style=for-the-badge&logo=pnpm&logoColor=white)
![SolidJS](https://img.shields.io/badge/SolidJS-v1.9-2C4F7C?style=for-the-badge&logo=solid&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-v7.0-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-v7.1-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![UnoCSS](https://img.shields.io/badge/UnoCSS-v66.5-333333?style=for-the-badge&logo=unocss&logoColor=white)
[![Edit in WebStorm](https://img.shields.io/badge/Edit_in-WebStorm-000000?style=for-the-badge&logo=webstorm&logoColor=white)](https://www.jetbrains.com/webstorm/)

## 快速开始

### 1. 使用模板新建仓库

在本仓库页面点击 **Use this template** → **Create a new repository**：

- 部署到 `https://<用户名>.github.io`：仓库名必须填 `<用户名>.github.io`，无需额外配置
- 部署到 `https://<用户名>.github.io/<仓库名>`：仓库名任意，同时需在 `vite.config.ts` 的 `defineConfig` 中添加 `base: '/<仓库名>/'`

模板生成的是全新仓库，只有一个初始提交，不含本仓库的历史。

### 2. 克隆到本地

```bash
git clone https://github.com/<用户名>/<仓库名>.git
cd <仓库名>
```

clone 会自动配置好远程仓库 `origin`，可直接提交推送。

### 3. 安装依赖并开发

```bash
pnpm i
pnpm dev
```

浏览器打开终端提示的地址即可预览，修改代码自动热更新。

### 4. 部署到 GitHub Pages

在仓库 **Settings** → **Pages** → **Source** 选择 **GitHub Actions**。此后每次推送到 `main` 分支都会自动构建并发布。


