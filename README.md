# My `ghostty` configuration :ghost:

This repository contains the configuration files I use to customize the [`ghostty`](https://github.com/ghostty-org/ghostty) terminal emulator.


## Keybindings

Conveniently, `ghostty` includes the features that I previously relied on the [`tmux`](https://github.com/tmux/tmux) terminal multiplexer to provide. I have ported my commonly used `tmux` keybindings for creating, resizing, and arranging splits in this config -- all of which use the `Ctrl+Space` key combination as a leader.

### Window splits

| Keybinding        | Command         |
|:-----------------:|:---------------:|
| `Ctrl+Space` `\`  | New split right |
| `Ctrl+Space` `\|` | New split left  |
| `Ctrl+Space` `-`  | New split down  |
| `Ctrl+Space` `_`  | New split up    |


## Installation

### Pre-requisites

1. Install [`ghostty` from download](https://ghostty.org/download)

### Clone the files in this repository for your local config

```bash
git clone https://github.com/jesdavpet/ghostty.git ~/.config/ghostty
```
