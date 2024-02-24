---
title: ":dotfiles"
date: 2021-08-19T13:06:28+05:30
slug: ""
description: ""
keywords: []
tags: []
math: false
toc: false
---

![machfiles image](/ss.png)

## Installing

!!! Note: We have a separate branch for mac install. Please check that out for macOS.

Clone into your `$HOME` directory or `~`

```bash
git clone https://github.com/sdatth/dotfiles.git $HOME/
# OR
git clone https://gitlab.com/sdatth/dotfiles.git $HOME/
```

### For Linux Distros

You will need `make` 

Run the command to install necessary packages and get my config files for your linux distribution
```bash
make [arch|debian|ubuntu|rhel]
```

### For FreeBSD

You will need `gmake` 

Run the command to install necessary packages and get my config files for FreeBSD
```bash
gmake freebsd
```

### Help

Use the help recipe to see available options
```bash
make help
```


#### Note Important:

Support for Arm64 is in the roadmap

This script will install files from 
- zsh-autosuggestions plugin          : https://github.com/zsh-users/zsh-autosuggestions
- zsh-syntax-highlighting plugin      : https://github.com/zsh-users/zsh-syntax-highlighting
- zsh-history-substring-search plugin : https://github.com/zsh-users/zsh-history-substring-search

This repo contains code/files from other repo, they are the original authors for this
- Vim Plug        : https://github.com/junegunn/vim-plug
- Nerd Fonts      : https://www.nerdfonts.com/
- Autojump plugin : https://github.com/wting/autojump
