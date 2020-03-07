[![Netlify Status](https://api.netlify.com/api/v1/badges/fd6ad7cc-383e-4780-9e24-f712727e6aa9/deploy-status)](https://app.netlify.com/sites/see-naomi-go/deploys)

Naomi See's blog created with the super slim [xity-starter](https://github.com/equinusocio/xity-starter) which is an 11ty starter project based on PostCSS and Parcel, with a RSS feed and Native Elements.





## Preconfigured tools

- [Eleventy][] for templates and site generation
- [PostCSS][] and [PostCSS Preset Env][] to process your CSS
- [cssnano][] to minimize, merge and optimize the CSS ouput
- [Parcel][] for a simple asset build pipeline
- [Turbolinks][] makes navigating your web application faster
- [What Input][] to show outline only when navigating with keyboard

[Eleventy]: https://11ty.dev "Static site generator"
[PostCSS]: https://postcss.org "A tool for transforming CSS with JavaScript"
[PostCSS Preset Env]: https://preset-env.cssdb.org "Use tomorrow’s CSS today"
[cssnano]: https://cssnano.co "A modular minifier based on the PostCSS ecosystem"
[Parcel]: https://parceljs.org "Web application bundler"
[Turbolinks]: https://github.com/turbolinks/turbolinks
[What Input]: https://github.com/ten1seven/what-input "A global utility for tracking the current input method"
[Native Elements]: https://native-elements.stackblitz.io
[eleventy-plugin-pwa]: https://github.com/okitavera/eleventy-plugin-pwa "An Eleventy plugin to generate service worker"
[Browsersync]: https://www.npmjs.com/package/browser-sync "Time-saving synchronised browser testing"
[Node.js]: https://nodejs.org/
[Yarn]: https://yarnpkg.com/ "Package Manager"

---

## Prerequisites

- [Node.js][] & npm
- [Yarn][]

## Usage

```bash
yarn install
```

### Running the local development mode

This command will run `parcel` and the local server (with [Browsersync][]) with auto reload.

```bash
yarn dev
```

### Building the production version

To generate your static site/blog you can run the following command. It will prepare the content assets and run optimisations for a production release.

```bash
yarn build
```

