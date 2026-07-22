# TannenWaddy 的个人博客

我的个人博客网站，基于 **SolidJS + Vite** 框架，使用 **UnoCSS** 编写样式，部署在 GitHub Pages。

🌐 在线访问：<https://tannenwaddy.github.io/>

## 技术栈

- [SolidJS](https://solidjs.com) — 响应式 UI 框架
- [Vite](https://vite.dev) — 构建与开发工具
- [UnoCSS](https://unocss.dev) — 原子化 CSS 引擎
- [TypeScript](https://www.typescriptlang.org) — 类型支持
- [pnpm](https://pnpm.io) — 包管理器
- GitHub Actions + GitHub Pages — 自动构建与部署

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
