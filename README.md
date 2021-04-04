# VSCode Scheme

[![build](https://github.com/jeandeaual/vscode-scheme/workflows/build/badge.svg)](https://github.com/jeandeaual/vscode-scheme/actions?query=workflow%3Abuild)

Scheme syntax highlighting for VSCode.

## Features

* Scheme syntax highlighting

## Requirements

* [VSCode](https://code.visualstudio.com/) 1.0.0 or newer

## Installation

1. Open the Extensions left panel in VSCode (Windows: Ctrl+Shift+X; MacOS: Cmd+Shift+X)
2. Type in `Scheme` in the search bar
3. Install the extension, then reload VSCode (Ctrl+R)

## Build

```sh
yarn install
npx vsce package
```

## Release Notes

See [here](CHANGELOG.md).

# Aknowledgements

This extension is based on egrachev's [`Scheme.tmLanguage`](https://github.com/egrachev/sublime-scheme/blob/master/Scheme.tmLanguage)
