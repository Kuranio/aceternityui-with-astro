# Astro using Aceternity UI Components

```sh
pnpm create astro@latest
```
```sh
pnpx astro add tailwind
```
```sh
pnpx astro add react
```
```sh
pnpm i framer-motion clsx tailwind-merge
```

![just-the-basics](https://github.com/withastro/astro/assets/2244813/a0a5533c-a856-4198-8470-2d67b1d7c554)
![just-the-basics](https://miro.medium.com/v2/resize:fit:1400/0*3GRHW4UEaZqWuYj2.png)

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── react/
│   │   │   ├── aceternityui/
│   │   │   │   └── component.tsx
│   │   │   └── usingcomponent.ts
│   │   └── component.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Astro Build : https://astro.build/

Aceternity UI : https://ui.aceternity.com/
