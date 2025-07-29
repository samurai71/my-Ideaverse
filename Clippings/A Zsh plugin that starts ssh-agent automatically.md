---
title: "sdiebolt/zsh-ssh-agent: A Zsh plugin that starts ssh-agent automatically."
source: "https://github.com/sdiebolt/zsh-ssh-agent"
author:
  - "[[sdiebolt]]"
published:
created: 2025-07-27
description: "A Zsh plugin that starts ssh-agent automatically. Contribute to sdiebolt/zsh-ssh-agent development by creating an account on GitHub."
tags:
  - "clippings"
---
[Skip to content](https://github.com/sdiebolt/#start-of-content)

A Zsh plugin that starts ssh-agent automatically.

### License

[View license](https://github.com/sdiebolt/zsh-ssh-agent/blob/main/LICENSE.md)

[Star](https://github.com/login?return_to=%2Fsdiebolt%2Fzsh-ssh-agent)

[Notifications](https://github.com/login?return_to=%2Fsdiebolt%2Fzsh-ssh-agent) You must be signed in to change notification settings

## sdiebolt/zsh-ssh-agent

## Folders and files

<table><thead><tr><th colspan="2"><span>Name</span></th><th colspan="1"><span>Name</span></th><th><p><span>Last commit message</span></p></th><th colspan="1"><p><span>Last commit date</span></p></th></tr></thead><tbody><tr><td colspan="3"><h2>Latest commit</h2><p><span><a href="https://github.com/sdiebolt/zsh-ssh-agent/commit/9086e635dd5b2a8ca1cb99989d29d1b9a23692c3">fix(ssh-agent): fix SSH socket persistence</a></span></p><p><span><a href="https://github.com/sdiebolt/zsh-ssh-agent/commit/9086e635dd5b2a8ca1cb99989d29d1b9a23692c3">9086e63</a> ·</span></p><div><h2>History</h2><a href="https://github.com/sdiebolt/zsh-ssh-agent/commits/main/"><span><span><span>3 Commits</span></span></span></a></div></td></tr><tr><td colspan="2"><p><a href="https://github.com/sdiebolt/zsh-ssh-agent/blob/main/LICENSE.md">LICENSE.md</a></p></td><td colspan="1"><p><a href="https://github.com/sdiebolt/zsh-ssh-agent/blob/main/LICENSE.md">LICENSE.md</a></p></td><td><p><a href="https://github.com/sdiebolt/zsh-ssh-agent/commit/a93dd48e0ebd741517d106d79f13662bd934ae69">Initial commit</a></p></td><td></td></tr><tr><td colspan="2"><p><a href="https://github.com/sdiebolt/zsh-ssh-agent/blob/main/README.md">README.md</a></p></td><td colspan="1"><p><a href="https://github.com/sdiebolt/zsh-ssh-agent/blob/main/README.md">README.md</a></p></td><td><p><a href="https://github.com/sdiebolt/zsh-ssh-agent/commit/a93dd48e0ebd741517d106d79f13662bd934ae69">Initial commit</a></p></td><td></td></tr><tr><td colspan="2"><p><a href="https://github.com/sdiebolt/zsh-ssh-agent/blob/main/zsh-ssh-agent.plugin.zsh">zsh-ssh-agent.plugin.zsh</a></p></td><td colspan="1"><p><a href="https://github.com/sdiebolt/zsh-ssh-agent/blob/main/zsh-ssh-agent.plugin.zsh">zsh-ssh-agent.plugin.zsh</a></p></td><td><p><a href="https://github.com/sdiebolt/zsh-ssh-agent/commit/9086e635dd5b2a8ca1cb99989d29d1b9a23692c3">fix(ssh-agent): fix SSH socket persistence</a></p></td><td></td></tr><tr><td colspan="3"></td></tr></tbody></table>

## zsh-ssh-agent

A Zsh plugin that starts `ssh-agent` automatically if it is not already running.

## Install

Using the [⚡ Zap](https://www.zapzsh.com/) Zsh plugin manager, add the following to your `.zshrc`

```
plug "sdiebolt/zsh-ssh-agent"
```

To set a maximum lifetime when adding identities to `ssh-agent`, add the `lifetime` style to your `.zshrc` **before the line that installs the plugin**. The lifetime may be specified according to `sshd_config(5)` (see `TIME FORMATS`). If left unspecified, the default lifetime is forever.

```
zstyle :plugins:ssh-agent lifetime 4h
```

To automatically add keys to `ssh-agent`, add the following to your `~/.ssh/config` file:

```
AddKeysToAgent yes
```

## Credits

This plugin is based on the [Oh My Zsh](https://ohmyz.sh/) plugin [zsh-ssh-agent](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/ssh-agent). Unfortunately, the Oh My Zsh plugin cannot be installed as a standalone plugin using [⚡ Zap](https://www.zapzsh.com/).

## Releases

No releases published

## Packages

No packages published  

## Languages

- [Shell 100.0%](https://github.com/sdiebolt/zsh-ssh-agent/search?l=shell)

Copied!