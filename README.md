This is a fork of the deprecated [@robingenz/capacitor-android-dark-mode-support](https://github.com/capawesome-team/capacitor-android-dark-mode-support) Capacitor plugin which has been ported to work with newer Capacitor versions.

It has been created to maintain plugin functionality in WebView versions <= 100 (see [Issue 10](https://github.com/capawesome-team/capacitor-android-dark-mode-support/issues/10) for more info).

Installation:

```shell
# Capacitor 6
npm install @robingenz/capacitor-android-dark-mode-support@github:piotr-cz/capacitor-android-dark-mode-support#feature/capacitor-6

# Capacitor 5
npm install @robingenz/capacitor-android-dark-mode-support@github:piotr-cz/capacitor-android-dark-mode-support#feature/capacitor-5

# Capacitor 4
npm install @robingenz/capacitor-android-dark-mode-support@github:piotr-cz/capacitor-android-dark-mode-support#feature/capacitor-4
```

Below comes original readme.


## ⚠️ Deprecated repository

**Capacitor now officially supports dark mode on Android. See this [comment](https://github.com/ionic-team/capacitor/issues/4677#issuecomment-1126274884).**

-----

<p align="center"><br><img src="https://user-images.githubusercontent.com/236501/85893648-1c92e880-b7a8-11ea-926d-95355b8175c7.png" width="128" height="128" /></p>
<h3 align="center">Android Dark Mode Support</h3>
<p align="center"><strong><code>@robingenz/capacitor-android-dark-mode-support</code></strong></p>
<p align="center">
  Capacitor plugin to support dark mode on Android.
</p>

<p align="center">
  <img src="https://img.shields.io/maintenance/yes/2022?style=flat-square" />
  <a href="https://github.com/robingenz/capacitor-android-dark-mode-support/actions?query=workflow%3A%22CI%22"><img src="https://img.shields.io/github/workflow/status/robingenz/capacitor-android-dark-mode-support/CI/main?style=flat-square" /></a>
  <a href="https://www.npmjs.com/package/@robingenz/capacitor-android-dark-mode-support"><img src="https://img.shields.io/npm/l/@robingenz/capacitor-android-dark-mode-support?style=flat-square" /></a>
<br>
  <a href="https://www.npmjs.com/package/@robingenz/capacitor-android-dark-mode-support"><img src="https://img.shields.io/npm/dw/@robingenz/capacitor-android-dark-mode-support?style=flat-square" /></a>
  <a href="https://www.npmjs.com/package/@robingenz/capacitor-android-dark-mode-support"><img src="https://img.shields.io/npm/v/@robingenz/capacitor-android-dark-mode-support?style=flat-square" /></a>
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
<a href="#contributors-"><img src="https://img.shields.io/badge/all%20contributors-1-orange?style=flat-square" /></a>
<!-- ALL-CONTRIBUTORS-BADGE:END -->
</p>

## Maintainers

| Maintainer | GitHub                                    | Social                                        |
| ---------- | ----------------------------------------- | --------------------------------------------- |
| Robin Genz | [robingenz](https://github.com/robingenz) | [@robin_genz](https://twitter.com/robin_genz) |

## Installation

```bash
npm install @robingenz/capacitor-android-dark-mode-support
npx cap sync
```

### Variables

This plugin will use the following project variables (defined in your app’s `variables.gradle` file):
- `$androidxWebkitVersion` version of `androidx.webkit:webkit` (default: `1.2.0`)

## Configuration

No configuration required for this plugin.

## Demo

A working example can be found here: [robingenz/capacitor-plugin-demo](https://github.com/robingenz/capacitor-plugin-demo)

## Usage

The plugin only needs to be installed.

It enables the correct behavior of the [`prefers-color-scheme`](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-color-scheme) CSS media feature.

## Changelog

See [CHANGELOG.md](https://github.com/robingenz/capacitor-android-dark-mode-support/blob/main/CHANGELOG.md).

## License

See [LICENSE](https://github.com/robingenz/capacitor-android-dark-mode-support/blob/main/LICENSE).
