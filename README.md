# My `ghostty` configuration :ghost:

This repository contains the configuration files I use to customize the [`ghostty`](https://github.com/ghostty-org/ghostty) terminal emulator.


## Keybindings

Conveniently, `ghostty` includes the features that I previously relied on the [`tmux`](https://github.com/tmux/tmux) terminal multiplexer to provide. I have ported my commonly used `tmux` keybindings for creating, resizing, and arranging splits in this config -- all of which use the `Ctrl+Space` key combination as a leader.

### Create new splits

| Keybinding        | Command         |
|:-----------------:|:---------------:|
| `Ctrl+Space` `\`  | New split right |
| `Ctrl+Space` `\|` | New split left  |
| `Ctrl+Space` `-`  | New split down  |
| `Ctrl+Space` `_`  | New split up    |

### Navigate between splits

| Keybinding        | Command           |
|:-----------------:|:-----------------:|
| `Ctrl+Space` `h`  | Go to split right |
| `Ctrl+Space` `j`  | Go to split left  |
| `Ctrl+Space` `k`  | Go to split down  |
| `Ctrl+Space` `l`  | Go to split up    |
| `Ctrl+Space` `z`  | Zoom spli in/out  |

### Resize current split

| Keybinding        | Command             |
|:-----------------:|:-------------------:|
| `Ctrl+Space` `H`  | Resize split right  |
| `Ctrl+Space` `J`  | Resize split left   |
| `Ctrl+Space` `K`  | Resize split down   |
| `Ctrl+Space` `L`  | Resize split up     |
| `Ctrl+Space` `=`  | Equalize all splits |

### Close current surface (split → tab → window)

| Keybinding        | Command               |
|:-----------------:|:---------------------:|
| `Ctrl+Space` `x`  | Close current surface |


## Installation

### Pre-requisites

1. Install [`ghostty` from download](https://ghostty.org/download)

### Clone the files in this repository for your local config

```bash
git clone https://github.com/jesdavpet/ghostty.git ~/.config/ghostty
```

## Updating

### Pulling latest from GitHub

```bash
cd ~/.config/ghostty && git checkout origin/trunk
```

### Source (reload) local config changes

| Keybinding        | Command                        |
|:-----------------:|:------------------------------:|
| `Ctrl+Space` `s`  | Relaod config from source file |
