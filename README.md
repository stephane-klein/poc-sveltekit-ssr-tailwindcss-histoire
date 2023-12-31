# SvelteKit SSR + TailwindCSS + Histoire POC

Components and libraries:

- [x] [SSR](https://kit.svelte.dev/docs/page-options#ssr) [SvelteKit](https://github.com/sveltejs/kit) with [Hydration](https://kit.svelte.dev/docs/glossary#hydration)
- [x] [tailwindcss](https://github.com/tailwindlabs/tailwindcss)
- [x] [Histoire](https://histoire.dev/)

Tooling:

- ✅ [asdf](https://asdf-vm.com/)
- ✅ [NodeJS](https://nodejs.org/en/)
- ✅ [pnpm](https://pnpm.io/)
- ✅ [Prettier](https://prettier.io/)
- ✅ [ESlint](https://eslint.org/)

## Getting started

```sh
$ asdf install
```

```sh
$ pnpm install
```

Start web server:

```sh
$ pnpm run dev
```

Go to http://localhost:5173

## Start Histoire

```sh
$ pnpm run story:dev
```

Go to http://localhost:6006

## Prettier

Launch Prettier check:

```sh
$ pnpm run prettier-check
```

Apply Prettier fix example:

```sh
$ pnpm run prettier src/app.html
```

## ESlint

```sh
$ pnpm run eslint
```
