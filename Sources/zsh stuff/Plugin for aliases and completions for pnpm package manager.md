---
title: "empresslabs/pnpm.plugin.zsh: Plugin for aliases and completions for pnpm package manager."
source: https://github.com/empresslabs/pnpm.plugin.zsh
author:
  - "[[empresslabs]]"
  - "[[baliestri]]"
published:
created: 2025-07-27
description: Plugin for aliases and completions for pnpm package manager. - empresslabs/pnpm.plugin.zsh
tags:
  - clippings
  - source
---
Plugin for aliases and completions for pnpm package manager.

[MIT license](https://github.com/empresslabs/pnpm.plugin.zsh/blob/develop/LICENSE.md)

<table><thead><tr><th colspan="2"><span>Name</span></th><th colspan="1"><span>Name</span></th><th><p><span>Last commit message</span></p></th><th colspan="1"><p><span>Last commit date</span></p></th></tr></thead><tbody><tr><td colspan="3"><p><span><a href="https://github.com/empresslabs/pnpm.plugin.zsh/commit/07fa737d38ec0ee67caa81b9f6cec7ac73593072">Merge tag 'v1.0.1' into develop</a></span></p><p><span><a href="https://github.com/empresslabs/pnpm.plugin.zsh/commit/07fa737d38ec0ee67caa81b9f6cec7ac73593072">07fa737</a> ·</span></p><p><a href="https://github.com/empresslabs/pnpm.plugin.zsh/commits/develop/"><span><span><span>16 Commits</span></span></span></a></p></td></tr><tr><td colspan="2"><p><a href="https://github.com/empresslabs/pnpm.plugin.zsh/tree/develop/.github">.github</a></p></td><td colspan="1"><p><a href="https://github.com/empresslabs/pnpm.plugin.zsh/tree/develop/.github">.github</a></p></td><td><p><a href="https://github.com/empresslabs/pnpm.plugin.zsh/commit/b34006f1d9c5f18fa8daf99b0c79d72be674a96e">chore: add auto-release workflow</a></p></td><td></td></tr><tr><td colspan="2"><p><a href="https://github.com/empresslabs/pnpm.plugin.zsh/tree/develop/completions">completions</a></p></td><td colspan="1"><p><a href="https://github.com/empresslabs/pnpm.plugin.zsh/tree/develop/completions">completions</a></p></td><td><p><a href="https://github.com/empresslabs/pnpm.plugin.zsh/commit/15ca38c23da1be8d80de37bbb041d15ade403c68">chore: move _pnpm to completions directory</a></p></td><td></td></tr><tr><td colspan="2"><p><a href="https://github.com/empresslabs/pnpm.plugin.zsh/blob/develop/.editorconfig">.editorconfig</a></p></td><td colspan="1"><p><a href="https://github.com/empresslabs/pnpm.plugin.zsh/blob/develop/.editorconfig">.editorconfig</a></p></td><td><p><a href="https://github.com/empresslabs/pnpm.plugin.zsh/commit/7ea3ae2fde01afbfdce0431b8a1a33cc0c636db4">initial commit</a></p></td><td></td></tr><tr><td colspan="2"><p><a href="https://github.com/empresslabs/pnpm.plugin.zsh/blob/develop/.gitignore">.gitignore</a></p></td><td colspan="1"><p><a href="https://github.com/empresslabs/pnpm.plugin.zsh/blob/develop/.gitignore">.gitignore</a></p></td><td><p><a href="https://github.com/empresslabs/pnpm.plugin.zsh/commit/7ea3ae2fde01afbfdce0431b8a1a33cc0c636db4">initial commit</a></p></td><td></td></tr><tr><td colspan="2"><p><a href="https://github.com/empresslabs/pnpm.plugin.zsh/blob/develop/LICENSE.md">LICENSE.md</a></p></td><td colspan="1"><p><a href="https://github.com/empresslabs/pnpm.plugin.zsh/blob/develop/LICENSE.md">LICENSE.md</a></p></td><td><p><a href="https://github.com/empresslabs/pnpm.plugin.zsh/commit/5f697c0b6920037b09304528f72430e435a53962">chore: update LICENSE year</a></p></td><td></td></tr><tr><td colspan="2"><p><a href="https://github.com/empresslabs/pnpm.plugin.zsh/blob/develop/README.md">README.md</a></p></td><td colspan="1"><p><a href="https://github.com/empresslabs/pnpm.plugin.zsh/blob/develop/README.md">README.md</a></p></td><td><p><a href="https://github.com/empresslabs/pnpm.plugin.zsh/commit/b5279f863be7a096e1122ae5d27bf195d3284b49">chore: update zstyle option</a></p></td><td></td></tr><tr><td colspan="2"><p><a href="https://github.com/empresslabs/pnpm.plugin.zsh/blob/develop/pnpm.plugin.zsh">pnpm.plugin.zsh</a></p></td><td colspan="1"><p><a href="https://github.com/empresslabs/pnpm.plugin.zsh/blob/develop/pnpm.plugin.zsh">pnpm.plugin.zsh</a></p></td><td><p><a href="https://github.com/empresslabs/pnpm.plugin.zsh/commit/b5279f863be7a096e1122ae5d27bf195d3284b49">chore: update zstyle option</a></p></td><td></td></tr><tr><td colspan="3"></td></tr></tbody></table>

[![pnpm.plugin.zsh](https://github.com/empresslabs/pnpm.plugin.zsh/raw/develop/.github/assets/night.svg)](https://github.com/empresslabs/#gh-dark-mode-only) [![pnpm.plugin.zsh](https://github.com/empresslabs/pnpm.plugin.zsh/raw/develop/.github/assets/day.svg)](https://github.com/empresslabs/#gh-light-mode-only)

Plugin for aliases and completions for `pnpm` package manager.

## Installation

#### oh-my-zsh

```
git clone https://github.com/empresslabs/pnpm.plugin.zsh.git $ZSH_CUSTOM/plugins/pnpm
```
```
~/.zshrc
plugins=(... pnpm)
```

#### zinit

```
zinit light empresslabs/pnpm.plugin.zsh
```

#### zi

```
zi light empresslabs/pnpm.plugin.zsh
```

#### zgenom

```
zgenom load empresslabs/pnpm.plugin.zsh
```

#### zplug

```
zplug empresslabs/pnpm.plugin.zsh
```

## Settings

```
zstyle ":empresslabs:pnpm:completion" legacy-completion yes
```

Add this line to your `~/.zshrc` file to use the plugin-defined completions. If you prefer to use pnpm's built-in completions, remove this line.

## Aliases

| Alias | Command | Description |
| --- | --- | --- |
| pn | `pnpm` | The *`pnpm`* command |
| pnx | `pnpm dlx` | Fetch a package, load it and run command |
| pna | `pnpm add` | Install a package in dependencies (`package.json`) |
| pnad | `pnpm add --save-dev` | Install a package in devDependencies (`package.json`) |
| pnap | `pnpm add --save-peer` | Install a package in peerDependencies (`package.json`) |
| pnb | `pnpm run build` | Run the build script defined in `package.json` |
| pnd | `pnpm run dev` | Run the dev script defined in `package.json` |
| pnga | `pnpm add --global` | Install packages globally on your operating system |
| pngls | `pnpm list --global` | Lists global installed packages |
| pngrm | `pnpm remove --global` | Remove global installed packages from your OS |
| pngu | `pnpm update --global` | Upgrade packages installed globally to their latest version |
| pnh | `pnpm help` | Show help for a *`pnpm`* command |
| pnau | `pnpm audit` | Checks for known security issues with the installed packages |
| pnwhy | `pnpm why` | Shows the packages that depend on given package |
| pni | `pnpm init` | Interactively creates or updates a `package.json` file |
| pnin | `pnpm install` | Install dependencies defined in `package.json` |
| pnun | `pnpm uninstall` | Uninstall dependencies defined in `package.json` |
| pnln | `pnpm run lint` | Run the lint script defined in `package.json` |
| pndoc | `pnpm run doc` | Run the doc script defined in `package.json` |
| pnls | `pnpm list` | List installed packages |
| pnout | `pnpm outdated` | Check for outdated package dependencies |
| pnrm | `pnpm remove` | Remove installed packages |
| pnrun | `pnpm run` | Run a defined package script |
| pns | `pnpm run serve` | Start the dev server |
| pnst | `pnpm start` | Run the start script defined in `package.json` |
| pnt | `pnpm test` | Run the test script defined in `package.json` |
| pntc | `pnpm test --coverage` | Run the test script defined in `package.json` with coverage |
| pnui | `pnpm update --interactive` | Prompt for which outdated packages to upgrade |
| pnuil | `pnpm update --interactive --latest` | Prompt for which outdated packages to upgrade to the latest available version |
| pnup | `pnpm update` | Upgrade packages to their latest version |
| pnsv | `pnpm server` | Manage a *`pnpm`* store server |
| pnpub | `pnpm publish` | Publishes a package to the registry |
| pnset | `pnpm setup` | Sets up pnpm |

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/empresslabs/pnpm.plugin.zsh/blob/develop/LICENSE) file for details.

## Releases 2

[\+ 1 release](https://github.com/empresslabs/pnpm.plugin.zsh/releases)

## Languages

- [Shell 100.0%](https://github.com/empresslabs/pnpm.plugin.zsh/search?l=shell)