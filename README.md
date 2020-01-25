Dotfiles
========

## Install
1. Install `git` and `zsh`
2. `git --git-dir=$HOME/.dotfiles/ --work-tree=$HOME clone https://github.com/mobec/dotfiles`
3. chsh -s $(which zsh)

## Update
You can use the `dotfile` alias to use git with the workspace pointing to your home directory.

For example use  `dotfile pull` to get the latest dotfiles

