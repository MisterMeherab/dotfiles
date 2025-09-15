# Dotfiles by MisterMeherab

> Personal dotfiles for a beautiful, productive Linux setup.

## Features & Tools

- **Hyprland**: Dynamic tiling Wayland compositor for a modern, customizable desktop experience.
- **Zsh**: Powerful shell with Oh My Zsh, custom prompts, and plugins for productivity.
- **Neovim (nvim)**: Highly-configured text editor for coding, writing, and more.
- **WezTerm**: GPU-accelerated terminal emulator with advanced features and custom themes.
- **Other Fancy Tools**:
  - **Starship**: Minimal, fast, and customizable shell prompt.
  - **Fzf**: Fuzzy finder for fast navigation.
  - **Tmux**: Terminal multiplexer for session management.
  - **Git**: Aliases and configuration for efficient version control.
  - **Bat**: Cat clone with syntax highlighting.
  - **Ripgrep**: Fast searching in files.
  - **LSD**: Modern replacement for `ls`.
  - **Nerd Fonts**: Patched fonts for icons and glyphs.

## Installation

> **Warning:** These dotfiles are tailored for my workflow. Review before using!


### 1. Clone the repo

```zsh
git clone https://github.com/MisterMeherab/dotfiles ~/.dotfiles
```


### 2. Run the setup script (if available)

```zsh
cd ~/.dotfiles
./install.sh
```



### Using GNU Stow (Recommended)

GNU Stow makes managing dotfiles easy and clean. Each config should be in its own folder (e.g., `zsh/`, `nvim/`, `hypr/`).

```zsh
cd ~/.dotfiles
stow zsh
stow nvim
stow hypr
stow wezterm
# ...other configs
```


### 3. Install dependencies

- Hyprland, Zsh, Neovim, WezTerm, Starship, Fzf, Tmux, Bat, Ripgrep, LSD, Nerd Fonts
- Use your distro's package manager (e.g., `pacman`, `apt`, `dnf`)


## Screenshots

> Add screenshots of your setup here!

## Credits

- Inspired by many dotfile repos and r/unixporn
- See individual config files for more info

## License

MIT
