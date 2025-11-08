# The old MDN Change History Reader

> [!WARNING]
> This project version is an archive using the date diff method. This repository is not maintained because the current version is on the main repository [tristantheb/history-content](https://github.com/tristantheb/history-content).

This project provides a live tool to explore the edit history of MDN Web Docs locales.
Using comparative text analysis between document versions of en-US and the selected locale.

[![CD | Update deployed gitHub pages](https://github.com/tristantheb/archive-history-content/actions/workflows/update_pages.yaml/badge.svg?branch=main)](https://github.com/tristantheb/archive-history-content/actions/workflows/update_pages.yaml)

## Usage

Go to the [deployed site](https://tristantheb.github.io/archive-history-content/) and select a locale by adding `?locale=` and the locale following the folder names in the [MDN Translated Content repository](github.com/mdn/translated-content).

### Badges of a page

To use a badge of a page, you need to use the next URL format:

`https://tristantheb.github.io/archive-history-content/badges/<locale>/<path>.svg`

For example:

`https://tristantheb.github.io/archive-history-content/badges/fr/web/html.svg`

#### Results

![Badge of the french page Web/HTML on MDN displaying the current translation status](https://tristantheb.github.io/archive-history-content/badges/fr/web/html.svg)

## How it's working

The project deploy an updated version of the status every day at 1 AM UTC.

## License

[Mozilla Public License Version 2.0](LICENSE)
