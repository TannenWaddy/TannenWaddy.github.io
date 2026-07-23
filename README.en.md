# TannenWaddy's Personal Blog

> This site has just been set up and is still under development. Stay tuned.
>
> Translated by the Kimi K3 model. If you find any translation inaccuracies, please submit a PR to let me know the correct translation.

![License](https://img.shields.io/github/license/TannenWaddy/TannenWaddy.github.io?color=blue&style=for-the-badge)
![pnpm](https://img.shields.io/badge/pnpm-v11.15-F69220?style=for-the-badge&logo=pnpm&logoColor=white)
![SolidJS](https://img.shields.io/badge/SolidJS-v1.9-2C4F7C?style=for-the-badge&logo=solid&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-v7.0-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-v7.1-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![UnoCSS](https://img.shields.io/badge/UnoCSS-v66.5-333333?style=for-the-badge&logo=unocss&logoColor=white)
[![Edit in WebStorm](https://img.shields.io/badge/Edit_in-WebStorm-000000?style=for-the-badge&logo=webstorm&logoColor=white)](https://www.jetbrains.com/webstorm/)

## Local Development

### 1. Create a repository from this template

On this repository page, click **Use this template** → **Create a new repository**:

- To deploy to `https://<username>.github.io`: the repository name must be `<username>.github.io`; no extra configuration needed
- To deploy to `https://<username>.github.io/<repo>`: any repository name works, but you must add `base: '/<repo>/'` to `defineConfig` in `vite.config.ts`

The template creates a fresh repository with a single initial commit and does not include this repository's history.

### 2. Clone to local

```bash
git clone https://github.com/<username>/<repo>.git
cd <repo>
```

Cloning automatically configures the remote `origin`, so you can commit and push right away.

### 3. Install dependencies and develop

```bash
pnpm i
pnpm approve-builds
pnpm dev
```

Open the URL shown in the terminal to preview; code changes hot-reload automatically.

### 4. Deploy to GitHub Pages

In the repository, go to **Settings** → **Pages** → **Source** and select **GitHub Actions**. Every push to the `main` branch will then be built and published automatically.
