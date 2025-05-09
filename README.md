# My `ghostty` configuration :ghost:

This repository contains the configuration files I use to customize the [`ghostty`](https://github.com/ghostty-org/ghostty) terminal emulator.


## Keybindings

Conveniently, `ghostty` includes the features that I previously relied on the [`tmux`](https://github.com/tmux/tmux) terminal multiplexer to provide.

I have ported my commonly used `tmux` keybindings for creating, resizing, and arranging splits in this config -- all of which use the `Ctrl+Space` key combination as `<Leader>`.

These keybindings are similar to [`LazyVim` default keymaps](https://www.lazyvim.org/keymaps), because I am also lazy, and I don't want to memorize more than I have to.

### Create new splits

| Keybinding         | Command         |
|:------------------:|:---------------:|
| `<Leader>` `\|`    | New split right |
| `<Leader>` `\\\`   | New split left  |
| `<Leader>` `-`     | New split down  |
| `<Leader>` `_`     | New split up    |

### Navigate between splits

| Keybinding           | Command           |
|:--------------------:|:-----------------:|
| `<Leader>` `→`       | Go to split right |
| `<Leader>` `←`       | Go to split left  |
| `<Leader>` `↓`       | Go to split down  |
| `<Leader>` `↑`       | Go to split up    |
| `<Leader>` `z`       | Zoom split in/out |

### Resize current split

| Keybinding             | Command             |
|:----------------------:|:-------------------:|
| `<Leader>` `Shift` `→` | Resize split right  |
| `<Leader>` `Shift` `←` | Resize split left   |
| `<Leader>` `Shift` `↓` | Resize split down   |
| `<Leader>` `Shift` `↑` | Resize split up     |
| `<Leader>` `=`         | Equalize all splits |

### Close current surface (split → tab → window)

| Keybinding        | Command               |
|:-----------------:|:---------------------:|
| `<Leader>` `x`    | Close current surface |


## Installation

### Pre-requisites

1. Install [`ghostty` from download](https://ghostty.org/download)

### Clone the files in this repository for your local config

```bash
git clone https://github.com/jesdavpet/.ghostty.git ~/.config/ghostty
```

## Updating

### Pulling latest from GitHub

```bash
cd ~/.config/ghostty && git checkout origin/trunk
```

### Source (reload) local config changes

| Keybinding        | Command                        |
|:-----------------:|:------------------------------:|
| `<Leader>` `s`    | Relaod config from source file |
