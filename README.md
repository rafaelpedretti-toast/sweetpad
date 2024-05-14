# SweetPad (beta) <img valign="middle" alt="SweetPad logo" width="40" src="./images/logo.png" />

<!-- [![Discord](https://img.shields.io/badge/SweetPad-Discord-blue?logo=discord&logoColor=white&link=https%3A%2F%2Fdiscord.gg%2FXZwRtQ5dew)](https://discord.gg/XZwRtQ5dew) -->

[![Twitter](https://img.shields.io/twitter/follow/sweetpad_dev?style=social&logo=twitter)](https://twitter.com/sweetpad_dev)
[![GitHub](https://img.shields.io/github/stars/sweetpad-dev/sweetpad?style=social)](https://github.com/sweetpad-dev/sweetpad)
[![Github Sponsor](https://img.shields.io/github/sponsors/sweetpad-dev)](https://github.com/sponsors/sweetpad-dev)

Develop Swift/iOS projects using VSCode.

The long-term goal is to make VSCode as a viable alternative to Xcode for iOS development, by integrating open-source
tools such as **swift-format**, **swiftlint**, **xcodebuild**, **xcrun**, **xcode-build-server**, **sourcekit-lsp**, and
so on into VSCode.

![iOS simulator](./docs/images/build-demo.gif)

## Feature

- ✅ **[Autocomplete](./docs/wiki/autocomplete.md)** — setup autocomplete using
  [xcode-build-server](https://github.com/SolaWing/xcode-build-server)
- 🛠️ **[Build & Run](./docs/wiki/build.md)** — build and run application using
  [xcodebuild](https://developer.apple.com/library/archive/technotes/tn2339/_index.html)
- 💅🏼 **[Format](./docs/wiki/format.md)** — format files using [swift-format](https://github.com/apple/swift-format) or other formatter of your choice
- 📱 **[Simulator](./docs/wiki/simulator.md)** — manage iOS simulators
- 🛠️ **[Tools](./docs/wiki/tools.md)** — manage essential iOS development tools using [Homebrew](https://brew.sh/)
- 🪲 **[Debug](./docs/wiki/debug.md)** — debug iOS applications using
  [CodeLLDB](https://marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb)

> 💡 If you have any ideas, please open an issue or start a discussion on the
> [SweetPad](https://github.com/sweetpad-dev/sweetpad) GitHub repository.

## Requirements

1. 🍏 MacOS — Other platforms are currently not supported
2. 📱 Xcode — Required for building and running iOS apps via `xcodebuild`

## Changelog

All notable changes to the "sweetpad" extension you can find in the [CHANGELOG.md](./CHANGELOG.md).

## License

This extension is licensed under the [MIT License](./LICENSE.md).
