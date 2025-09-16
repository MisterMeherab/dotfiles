# Dotfiles

My personal dotfiles managed with GNU Stow.

## Setup

1. Clone the repository:

```zsh
git clone https://github.com/MisterMeherab/dotfiles ~/.dotfiles
````

```zsh
cd ~/.dotfiles
```

2.Use automation script to symlink the configs you want:

```zsh
chmod +x install.sh
```

```zsh
./install.sh
```

3.Alternatively, you can manually use `stow` to symlink specific configurations. For example:

```zsh
stow zsh     # for zsh config
```

```zsh
stow hypr    # for hyprland config
```

```zsh
stow nvim    # for neovim config
```

## Add more as needed

## License

MIT
