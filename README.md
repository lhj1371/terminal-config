# Terminal Configuration
My personal terminal configuration for setting up shell and neovim environments.

- Install zsh, oh-my-zsh, powerlevel10k, neovim(>=0.5.0), vim-plug, nodejs
- For neovim setting including coc.nvim and treesitter, copy `nvim` to `$HOME/.config` and then run `:PlugInstall` and `:CocInstall coc-pyright` in neovim.
- To easily manage dotfiles in `$HOME`, run followings. Use `dotgit` to manage dotfiles. (See [here](https://velog.io/@wannte/dotfile%EC%9D%84-%ED%8E%B8%ED%95%98%EA%B2%8C-%EA%B4%80%EB%A6%AC%ED%95%98%EB%8A%94-%EB%B0%A9%EB%B2%95with-Bare-Git-repository) for details)
```
git clone --bare https://github.com/LambdaLee/terminal-config.git $HOME/.termconf
git --git-dir=$HOME/.termconf --work-tree=$HOME checkout
zsh
dotgit config --local status.showUntrackedFiles no
dotgit status
```
