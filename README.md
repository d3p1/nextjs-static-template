<div align=center>

# [NEXT.JS STATIC TEMPLATE]

[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://github.com/prettier/prettier)
[![Release](https://github.com/d3p1/nextjs-static-template/actions/workflows/release.yml/badge.svg)](https://github.com/d3p1/nextjs-static-template/actions/workflows/release.yml)
[![semantic-release: angular](https://img.shields.io/badge/semantic--release-angular-e10079?logo=semantic-release)](https://github.com/semantic-release/semantic-release)

</div>

## Introduction

A template to build things using [`Next.js`](https://nextjs.org/) and its [`static`](https://nextjs.org/docs/app/guides/static-exports) mode.

It comes with a [GitHub Action](./.github/workflows/publish.yml) to automatically deploy the app to [GitHub Pages](https://docs.github.com/en/pages). On top of that, it implements [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) with [`commitlint`](https://commitlint.js.org/) and [`husky`](https://typicode.github.io/husky/) to [automate the generation of releases](./.github/workflows/release.yml). Finally, it also brings [`prettier`](https://prettier.io/) as coding formatter.

> [!NOTE]
> The used [`commitlint` configuration](https://github.com/d3p1/commitlint-config) forces you to write commit messages with the following format: `<type>(<scope>): <description> [<issue-number>]`.

> [!NOTE]
> This template comes with a [startup script](./.idea/runConfigurations/Dev.xml) for [WebStorm](https://www.jetbrains.com/webstorm/). However, the script will only run if this template is used inside a [`docknext`](https://github.com/d3p1/docknext) environment with the following folder structure: a `<doc-root>/infra` folder where the `docker` files/services live, and a `<doc-root>/www` folder where this template lives. 

## Usage

Update the [`README.md`](README.md), specifically the badges.

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
