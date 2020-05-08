# dotfiles

[![Circle CI](https://circleci.com/gh/reo11/dotfiles.svg?style=shield&circle-token=ad0dde00aa79d62e4d8becd310868691b0e82995)](https://circleci.com/gh/reo11/dotfiles)

## Overview

My home dotfiles

![overview](https://raw.githubusercontent.com/reo11/img/master/dotfiles/overview.png)


## Install

1. Download
`$ git clone https://github.com/reo11/dotfiles.git`
2. Install
`$ ./dotfiles/.bin/dotsinstaller.sh`
 (NoGUI)
`$ ./dotfiles/.bin/dotsinstaller.sh --no-gui`
3. vim plugin install
`$ vi +PlugInstall` or `:PlugInstall` after vim boot
4. zsh plugin install
`$ exec zsh`
5. Enjoy!


### Temporary Install

If you do not want to dirty your home directory

1. Download
```
$ mkdir /tmp/tmphome
$ cd /tmp/tmphome
$ git clone https://github.com/reo11/dotfiles.git
```
2. Set HOME environment temporary
`export HOME=/tmp/tmphome`
3. Install
`$ ./dotfiles/.bin/dotsinstaller.sh`
 (NoGUI)
`$ ./dotfiles/.bin/dotsinstaller.sh --no-gui`
4. vim plugin install
`$ vi +PlugInstall` or `:PlugInstall` after vim boot
5. zsh plugin install
`$ exec zsh`


## Components

- zsh
- neovim(vim)
- tmux
- i3-gaps(optional)


## Usage

### Frequently used shortcuts

#### tmux

|key|action|
|---|---|
|Alt-h/j/k/l|switch window|
|Alt-j|close window|
|Alt-k|create window|
|S-Up/Down/Left/Right|switch pane|

#### i3

|key|action|
|---|---|
|Mod-h/j/k/l|switch window|
|Mod-S-h/j/k/l|move window|
|Mod-C-S-h/j/k/l|move workspace|

