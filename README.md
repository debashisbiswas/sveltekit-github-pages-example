# SvelteKit on GitHub Pages Example

Minimal SvelteKit project demonstrating automatic deployment to GitHub Pages using GitHub Actions.

GitHub Pages only allows for static sites, so the site is built with [@sveltejs/adapter-static](https://github.com/sveltejs/kit/tree/master/packages/adapter-static).

Note that the root `+layout.ts` uses `export const prerender = true` to let the adapter know that all of the pages are prerenderable.
