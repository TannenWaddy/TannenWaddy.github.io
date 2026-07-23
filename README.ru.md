# Личный блог TannenWaddy

> Сайт только начал создаваться и ещё находится в разработке. Следите за обновлениями.
>
> Переведено моделью Kimi K3. Если вы обнаружили неточности в переводе, пожалуйста, отправьте PR с правильным переводом.

![License](https://img.shields.io/github/license/TannenWaddy/TannenWaddy.github.io?color=blue&style=for-the-badge)
![pnpm](https://img.shields.io/badge/pnpm-v11.15-F69220?style=for-the-badge&logo=pnpm&logoColor=white)
![SolidJS](https://img.shields.io/badge/SolidJS-v1.9-2C4F7C?style=for-the-badge&logo=solid&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-v7.0-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-v7.1-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![UnoCSS](https://img.shields.io/badge/UnoCSS-v66.5-333333?style=for-the-badge&logo=unocss&logoColor=white)
[![Edit in WebStorm](https://img.shields.io/badge/Edit_in-WebStorm-000000?style=for-the-badge&logo=webstorm&logoColor=white)](https://www.jetbrains.com/webstorm/)

## Локальная разработка

### 1. Создание репозитория из шаблона

На странице этого репозитория нажмите **Use this template** → **Create a new repository**:

- Для развёртывания на `https://<имя_пользователя>.github.io`: имя репозитория должно быть `<имя_пользователя>.github.io`; дополнительная настройка не требуется
- Для развёртывания на `https://<имя_пользователя>.github.io/<репозиторий>`: имя может быть любым, но нужно добавить `base: '/<репозиторий>/'` в `defineConfig` файла `vite.config.ts`

Шаблон создаёт новый репозиторий с одним начальным коммитом, без истории исходного репозитория.

### 2. Клонирование на локальный компьютер

```bash
git clone https://github.com/<имя_пользователя>/<репозиторий>.git
cd <репозиторий>
```

При клонировании удалённый репозиторий `origin` настраивается автоматически, можно сразу коммитить и отправлять изменения.

### 3. Установка зависимостей и разработка

```bash
pnpm i
pnpm approve-builds
pnpm dev
```

Откройте в браузере адрес, указанный в терминале, для предпросмотра; изменения кода применяются автоматически (горячая перезагрузка).

### 4. Развёртывание на GitHub Pages

В репозитории перейдите в **Settings** → **Pages** → **Source** и выберите **GitHub Actions**. После этого каждый push в ветку `main` будет автоматически собираться и публиковаться.
