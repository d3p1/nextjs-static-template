<div align=center>

# [NEXT.JS STATIC TEMPLATE]

[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://github.com/prettier/prettier)
[![Release](https://github.com/d3p1/nextjs-static-template/actions/workflows/release.yml/badge.svg)](https://github.com/d3p1/nextjs-static-template/actions/workflows/release.yml)
[![semantic-release: angular](https://img.shields.io/badge/semantic--release-angular-e10079?logo=semantic-release)](https://github.com/semantic-release/semantic-release)

</div>

## Introduction

A template to build things using [`Next.js`](https://nextjs.org/) and its [`static`](https://nextjs.org/docs/app/guides/static-exports) mode.

It comes with a [GitHub Action](./.github/workflows/publish.yml) to automatically deploy the app to [GitHub Pages](https://docs.github.com/en/pages).

## Usage

Update the following [`package.json`](package.json) settings:

- `description`
- `repository.url`
- `author`
- `bugs.url`
- `homepage`
- `keywords`

Update the following [`next.config.ts`](next.config.ts) settings:

- `basePath`

Finally, to deploy your app, run:

- `npm run build`

Then, you can serve the `./out` folder using any web server.

## Changelog

Detailed changes for each release are documented in [`CHANGELOG.md`](./CHANGELOG.md).

## License

This work is published under [MIT License](./LICENSE).

## Author

Always happy to receive a greeting on:

- [LinkedIn](https://www.linkedin.com/in/cristian-marcelo-de-picciotto/)
- [Web](https://d3p1.dev/)
