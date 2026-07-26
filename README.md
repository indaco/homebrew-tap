# Homebrew Tap [![Powered By: GoReleaser](https://img.shields.io/badge/powered%20by-goreleaser-green.svg?style=flat-square)](https://github.com/goreleaser)

Homebrew tap for [indaco](https://github.com/indaco) projects.

## Available Packages

| Package         | Description                                                                           |
| --------------- | ------------------------------------------------------------------------------------- |
| [malt](#malt)   | A lightweight Homebrew-compatible client with a native TUI.                           |
| [sley](#sley)   | A CLI tool for managing semantic versioning using a .version file.                    |
| [tempo](#tempo) | A CLI tool for managing assets and scaffolding components in templ-based Go projects. |

---

## malt

Homebrew's whole ecosystem, none of its weight - a single Zig binary with native post_install and a themeable TUI & CLI

**GitHub:** <https://github.com/indaco/malt>

---

## sley

CLI for semantic versioning using a simple .version file. Language-agnostic with plugins for git tagging, changelog generation, versioning policies and more.

**GitHub:** <https://github.com/indaco/sley>

---

## tempo

A CLI tool for managing assets and scaffolding components in templ-based Go projects.

**GitHub:** <https://github.com/indaco/tempo>

---

## Setup

```bash
brew tap indaco/tap
```

## Usage

### Install a package

```bash
brew install indaco/tap/<package-name>
```

### Upgrade a package

```bash
brew upgrade indaco/tap/<package-name>
```

### Uninstall a package

```bash
brew uninstall <package-name>
```

### Remove the Tap

```bash
brew untap indaco/tap
```
