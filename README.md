# Dotfiles Mac

Contains config files for MacOS, version controlled.

## Prerequisites

- Install [Homebrew](https://brew.sh/)

- Install [Ghosttly](https://ghostty.org/docs/install/binary)

Comes with sensible defaults and necessary nerd fonts out of the box

- Install [OhMyZSH](https://github.com/ohmyzsh/ohmyzsh/wiki)

Has it's own prerequisites, like installing ZSH

- Create symlinks for config files

In the root directory, symlink the bash and zsh profiles like so:

```bash
mv .zshrc .zshrc-old
ln -s ~/repos/dotfiles-mac/.zshrc ~/.zshrc
```

## Sensitive variables

For sensitive variables that should not be included in Git, add them in:

- .zshrc.local

## Frequently used apps

Currently I'm using the following apps:

- [Raycast](https://www.raycast.com/) app launcher
- [AltTab](https://alt-tab-macos.netlify.app) app switcher
- [Arc Browser](https://arc.net/download)
- [Boxy SVG](https://boxy-svg.com/) SVG editor
