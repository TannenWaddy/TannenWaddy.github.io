# TannenWaddy 的个人博客

我的个人博客网站，基于 **SolidJS + Vite** 框架，使用 **UnoCSS** 编写样式，部署在 GitHub Pages。

🌐 在线访问：<https://tannenwaddy.github.io/>

![License](https://img.shields.io/github/license/TannenWaddy/TannenWaddy.github.io?color=blue&style=flat-square)
![pnpm](https://img.shields.io/badge/pnpm-v11.15-F69220?style=flat-square&logo=pnpm)
![SolidJS](https://img.shields.io/badge/SolidJS-v1.9-2C4F7C?style=flat-square&logo=solid)
![TypeScript](https://img.shields.io/badge/TypeScript-v7.0-blue?style=flat-square&logo=typescript)
![Vite](https://img.shields.io/badge/Vite-v7.1-646CFF?style=flat-square&logo=vite)

## 本地开发

```bash
# 安装依赖
pnpm install

# 启动开发服务器（http://localhost:3000）
pnpm dev

# 构建生产版本到 dist/
pnpm build

# 本地预览构建产物
pnpm serve
```

## 部署

push 到 `main` 分支后，GitHub Actions 会自动构建并发布到 GitHub Pages。
