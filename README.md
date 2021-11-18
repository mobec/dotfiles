Dotfiles
========

## Install
1. Install `git` and `zsh`
2. `git --git-dir=$HOME/.dotfiles/ --work-tree=$HOME clone --bare --recurse-submodules https://github.com/mobec/dotfiles $HOME/.dotfiles`
3. `git --git-dir=$HOME/.dotfiles/ --work-tree=$HOME checkout`
4. `git --git-dir=$HOME/.dotfiles/ --work-tree=$HOME submodule update --init --recursive`
5. `chsh -s $(which zsh)`
6. `vim` and press enter to open vim anyway, then run `:PluginInstall` in vim

## Update
You can use the `dotfiles` alias to use git with the workspace pointing to your home directory.

For example use  `dotfiles pull` to get the latest dotfiles

