# Astro test

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```
/
├── dist/
├── public/
└── src/
    ├── components/
    ├── layouts/
    ├── pages/
    └── styles/
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any re-usable HTML/Astro/React/Vue/Svelte/Preact components.

Layouts, found in `src/layouts/`, build up the site, and take the content from pages and put them into HTML, or components, via attributes and slots.

Global styles can be found in `src/styles/global.less`, and imports from there.

Any static assets, like images, can be placed in the `public/` directory.

On build the static output gets sent to the `dist/` directory, for distribution.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                | Action                                           |
| :--------------------- | :----------------------------------------------- |
| `npm install`          | Installs dependencies                            |
| `npm run dev`          | Starts local dev server at `localhost:3000`      |
| `npm run build`        | Build your production site to `./dist/`          |
| `npm run preview`      | Preview your build locally, before deploying     |
| `npm run astro ...`    | Run CLI commands like `astro add`, `astro check` |
| `npm run astro --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).

