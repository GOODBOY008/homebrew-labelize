# homebrew-labelize

Homebrew tap for [labelize](https://github.com/GOODBOY008/labelize) — turn ZPL/EPL into pixels.

## Install

```bash
brew tap GOODBOY008/labelize
brew install labelize
```

## Usage

```bash
labelize convert label.zpl        # ZPL → PNG
labelize convert label.epl        # EPL → PNG
labelize serve --port 8080        # HTTP server
```

## How it works

The formula is automatically updated by the [labelize release workflow](https://github.com/GOODBOY008/labelize/actions) when a new version is tagged.
