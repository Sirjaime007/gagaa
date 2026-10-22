# Astro Lotus Starter

Starter template for building documentation sites with
[`@prosefly/astro-theme-lotus`](https://github.com/prosefly/astro-theme-lotus).

## Use This Template

```sh
npm create astro@latest -- --template prosefly/astro-template-lotus-starter
```

Or clone this repository directly:

```sh
npm install
npm run dev
```

## Project Structure

```text
src/
  content.config.ts      Registers the Lotus docs collection
  content/docs/          Your MDX documentation pages
theme.config.json        Configures navigation, docs navigation, search, and footer
```

Lotus reads MDX files from `src/content/docs` by default. This starter sets
`docsBase: '/'`, so `src/content/docs/index.mdx` renders as the site homepage at
`/`, and the docs entry page renders at `/overview/`.

## Commands

| Command | Description |
| --- | --- |
| `npm run dev` | Start the local dev server. |
| `npm run build` | Build the production site. |
| `npm run preview` | Preview the production build locally. |
| `npm run check` | Run Astro type and content checks. |

## Customize

Edit `theme.config.json` to change the site name, navigation, docs navigation,
appearance, search, footer links, and source links.
