# Our Little Universe

An interactive night-sky love letter with constellation notes, a moon secret and a birthday surprise. Built with React, TypeScript, Vite, Tailwind CSS, Framer Motion and Lucide icons.

## Live Website

https://azhardayo.github.io/website-2-our-universe/

## Run Locally

```sh
npm ci
npm run dev
```

To use a specific port:

```sh
npm run dev -- --port 5174
```

## Build

```sh
npm run build
npm run preview
```

The production files are generated in `dist/`.

## Personalize

Edit `src/data/content.ts` to change the love notes, poetry, promises, secret message, birthday wishes and other content. Optional music can be added under `public/assets/` and configured in the same content file.

## Deployment

This repository publishes the built `dist/` output through the `gh-pages` branch and GitHub Pages.
