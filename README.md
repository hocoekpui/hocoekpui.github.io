# Gallery

A photo-focused blog with a responsive feed, title and date search, and individual photo articles.

Visit the site at [hocoekpui.github.io](https://hocoekpui.github.io/).

## About This Repository

This repository contains the generated static site published through GitHub Pages. The application is built with Vue 3, Vue Router, and Vite. Its current interface is in Chinese.

## Deployment

The application source is maintained separately in the local `gallery-blog/gallery-vue` directory. From that source directory:

```sh
npm ci
npm run build
```

Copy the contents of `dist/` into this repository, commit the changes, and push to `master`. GitHub Pages publishes the root directory of that branch.

The site uses hash-based routes, such as `/#/article/<slug>`, and bundled article data. It does not require a running backend. The local administration API belongs to the source project and is used during development.
