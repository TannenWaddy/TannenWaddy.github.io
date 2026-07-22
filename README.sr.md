# Лични блог TannenWaddy

> Овај сајт је тек постављен и још је у развоју. Пратите даље.
>
> Превео модел Kimi K3. Ако пронађете било какве грешке у преводу, отворите Issue.

![License](https://img.shields.io/github/license/TannenWaddy/TannenWaddy.github.io?color=blue&style=for-the-badge)
![pnpm](https://img.shields.io/badge/pnpm-v11.15-F69220?style=for-the-badge&logo=pnpm&logoColor=white)
![SolidJS](https://img.shields.io/badge/SolidJS-v1.9-2C4F7C?style=for-the-badge&logo=solid&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-v7.0-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-v7.1-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![UnoCSS](https://img.shields.io/badge/UnoCSS-v66.5-333333?style=for-the-badge&logo=unocss&logoColor=white)
[![Edit in WebStorm](https://img.shields.io/badge/Edit_in-WebStorm-000000?style=for-the-badge&logo=webstorm&logoColor=white)](https://www.jetbrains.com/webstorm/)

## Локални развој

### 1. Креирајте репозиторијум из овог шаблона

На страници овог репозиторијума кликните на **Use this template** → **Create a new repository**:

- За распоређивање на `https://<корисничко_име>.github.io`: име репозиторијума мора бити `<корисничко_име>.github.io`; није потребна додатна конфигурација
- За распоређивање на `https://<корисничко_име>.github.io/<репозиторијум>`: било које име је у реду, али морате додати `base: '/<репозиторијум>/'` у `defineConfig` у `vite.config.ts`

Шаблон креира потпуно нови репозиторијум са само једним почетним комитом и не садржи историју овог репозиторијума.

### 2. Клонирајте локално

```bash
git clone https://github.com/<корисничко_име>/<репозиторијум>.git
cd <репозиторијум>
```

Клонирање аутоматски подешава удаљени репозиторијум `origin`, тако да одмах можете комитовати и гурати.

### 3. Инсталирајте зависности и развијајте

```bash
pnpm i
pnpm approve-builds
pnpm dev
```

Отворите у прегледачу адресу приказану у терминалу за преглед; промене у коду се аутоматски освежавају.

### 4. Распоредите на GitHub Pages

У репозиторијуму идите на **Settings** → **Pages** → **Source** и изаберите **GitHub Actions**. Од тада ће се сваки push на грану `main` аутоматски компајлирати и објављивати.
