# Dotfiles

My personal dotfiles managed with GNU Stow.

## Setup

1. Clone the repository:

```zsh
git clone https://github.com/MisterMeherab/dotfiles ~/.dotfiles
cd ~/.dotfiles
```

1. Use stow to symlink the configs you want:

```zsh
stow zsh     # for zsh config
stow hypr    # for hyprland config
stow nvim    # for neovim config
# etc...
```

## License

MIT
