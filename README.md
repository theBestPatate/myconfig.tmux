# My TMUX config

This is my current tmux config. Feel free to copy,change it as I did myself from other conf.

> TLDR:
- Vim based pane motion
- Catpuccin theme
- Bar
- Prefix: `<C-b>`

# Installation

1) Install Tmux with your package manager.
For debian-based distro(ubuntu, pop-os ...)

```bash
sudo apt install tmux
```


2) Clone this repo into .config/tmux directory

```
git clone https://github.com/theBestPatate/myconfig.tmux.git ~/.config/tmux
```

## Install Plugins

- **Install Plugins**: After starting tmux, press `<C-b> I` (Control + W followed by I) to install the plugins.
(Capitatlisation is important)

## Usage

- **Prefix Key**: The prefix key is set to `C-b` (Control + b).
- **Reload Configuration**: Press `<C-b> r` to reload the tmux configuration.
- **Create New SSH Window**: Press `<C-b> S` to open a new window for SSH.

## Configuration Overview

- **Mouse Support**: Enables mouse support for easier pane management.
- **Default Shell**: Sets the default shell to the user's current shell.
- **Pane Titles**: Configures titles for each pane.
- **1-Based Indexing**: Changes pane indexing to start from 1.
- **Truecolor Support**: Enables true color support.

## Customization

Feel free to modify the configuration to suit your preferences.

## Acknowledgments

- Catppuccin Theme
- TMUX Plugin Manager (TPM)
