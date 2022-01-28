<p align='center'>
  <img src='https://repository-images.githubusercontent.com/453208956/37af7f4a-2ec0-4d32-b239-eacd96094762' alt='Vitesse Lite with Tailwind - Opinionated Vite Starter Template' width='600'/>
</p>

<h6 align='center'>
<a href="https://vitesse-lite-tailwind.netlify.app">Live Demo</a>
</h6>

<h5 align='center'>
<b>Lightweight version of <a href="https://github.com/antfu/vitesse">Vitesse by Anthony Fu</a> with <a href="https://github.com/antfu/vitesse">TailwindCSS</a></b>
</h5>

<br>

## Features

- ⚡️ [Vue 3](https://github.com/vuejs/vue-next), [Vite 2](https://github.com/vitejs/vite), [pnpm](https://pnpm.js.org/), [ESBuild](https://github.com/evanw/esbuild) - born with fastness

- 🗂 [File based routing](./src/pages)

- 📦 [Components auto importing](./src/components)

- 🎨 [TailwindCSS](https://tailwindcss.com) - A utility-first CSS framework.

- 😃 Use icons from any icon sets in [Pure CSS](https://github.com/antfu/unocss/tree/main/packages/preset-icons)

- 🔥 Use the [new `<script setup>` style](https://github.com/vuejs/rfcs/pull/227)

- ✅ Use [Vitest](http://vitest.dev/) for unit and components testing

- 🦾 TypeScript, of course

- ☁️ Deploy on Netlify, zero-config


<br>

See [Vitesse](https://github.com/antfu/vitesse) for full featureset.


## Dropped Features from [Vitesse](https://github.com/antfu/vitesse)

- ~~i18n~~
- ~~Layouts~~
- ~~SSG~~
- ~~PWA~~
- ~~Markdown~~

## Pre-packed

### UI Frameworks

- [TailwindCSS](https://tailwindcss.com) - A utility-first CSS framework

### Icons

- [Iconify](https://iconify.design) - use icons from any icon sets [🔍Icônes](https://icones.netlify.app/)

### Plugins

- [Vue Router](https://github.com/vuejs/vue-router)
  - [`vite-plugin-pages`](https://github.com/hannoeru/vite-plugin-pages) - file system based routing
- [`unplugin-auto-import`](https://github.com/antfu/unplugin-auto-import) - Directly use Vue Composition API and others without importing
- [`unplugin-vue-components`](https://github.com/antfu/unplugin-vue-components) - components auto import
- [VueUse](https://github.com/antfu/vueuse) - collection of useful composition APIs

## Try it now!

### GitHub Template

[Create a repo from this template on GitHub](https://github.com/mariohamann/vitesse-lite-tailwind/generate).

### Clone to local

If you prefer to do it manually with the cleaner git history

```bash
npx degit mariohamann/vitesse-lite-tailwind my-vitesse-tailwind-app
cd my-vitesse-tailwind-app
pnpm i # If you don't have pnpm installed, run: npm install -g pnpm
```
