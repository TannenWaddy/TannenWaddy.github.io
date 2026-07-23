# Blog personal de TannenWaddy

> Este sitio acaba de crearse y aún está en desarrollo. Mantente atento.
>
> Traducido por el modelo Kimi K3. Si encuentras alguna traducción inexacta, por favor envía un PR para informarme de la traducción correcta.

![License](https://img.shields.io/github/license/TannenWaddy/TannenWaddy.github.io?color=blue&style=for-the-badge)
![pnpm](https://img.shields.io/badge/pnpm-v11.15-F69220?style=for-the-badge&logo=pnpm&logoColor=white)
![SolidJS](https://img.shields.io/badge/SolidJS-v1.9-2C4F7C?style=for-the-badge&logo=solid&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-v7.0-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-v7.1-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![UnoCSS](https://img.shields.io/badge/UnoCSS-v66.5-333333?style=for-the-badge&logo=unocss&logoColor=white)
[![Edit in WebStorm](https://img.shields.io/badge/Edit_in-WebStorm-000000?style=for-the-badge&logo=webstorm&logoColor=white)](https://www.jetbrains.com/webstorm/)

## Desarrollo local

### 1. Crear un repositorio desde esta plantilla

En la página de este repositorio, haz clic en **Use this template** → **Create a new repository**:

- Para desplegar en `https://<usuario>.github.io`: el nombre del repositorio debe ser `<usuario>.github.io`; no se necesita configuración adicional
- Para desplegar en `https://<usuario>.github.io/<repositorio>`: cualquier nombre funciona, pero debes agregar `base: '/<repositorio>/'` en `defineConfig` de `vite.config.ts`

La plantilla crea un repositorio completamente nuevo con un solo commit inicial y no incluye el historial de este repositorio.

### 2. Clonar en local

```bash
git clone https://github.com/<usuario>/<repositorio>.git
cd <repositorio>
```

Al clonar se configura automáticamente el remoto `origin`, por lo que puedes hacer commit y push de inmediato.

### 3. Instalar dependencias y desarrollar

```bash
pnpm i
pnpm approve-builds
pnpm dev
```

Abre en el navegador la dirección que muestra la terminal para previsualizar; los cambios en el código se recargan en caliente automáticamente.

### 4. Desplegar en GitHub Pages

En el repositorio, ve a **Settings** → **Pages** → **Source** y selecciona **GitHub Actions**. A partir de entonces, cada push a la rama `main` se compilará y publicará automáticamente.
