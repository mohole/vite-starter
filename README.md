# mohole-vite-starter

> Simple starter kit boilerplate based on [Vite.js vanilla template](https://vitejs.dev/guide/#trying-vite-online).

## How to use

Use degit to quickly clone the repo to a new folder:

```bash
npx degit mohole/vite-starter my-new-project
```

then install dependencies

```bash
cd my-new-project
npm install
# or "npm i" as shortcut...
```

and get started:

```bash
npm run dev
```

This will start a `Rollup development server` instance in `hot-reload` mode (_this will automatically update your browser when you apply any changes to the source files_), your project will be exposed at `localhost:3000`.

To create the optimized files to publish to whaterver static hosting you choose, just run:

```bash
npm run build
```

the result will be available in the `./dist` folder.

## Templates

There are a few different templates available in various branches, the default template use plain `HTML`+`CSS`+`Javascript`.

Template with SASS:

```bash
npx degit mohole/vite-starter#sass
```

Template with SASS & Bootstrap v5:

```bash
npx degit mohole/vite-starter#bootstrap
```

Template with Tailwind:

```bash
npx degit mohole/vite-starter#tailwind
```

## Customizations

To customize and evolve the complexity of the project you can follow the [official Vite.js documentation](https://vitejs.dev/guide/#overview).

## License

Released under the [MIT license](LICENSE).
