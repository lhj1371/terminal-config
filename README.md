# Terminal Configuration
My personal terminal configuration for setting up shell and neovim environments.

- Install zsh, oh-my-zsh, powerlevel10k, neovim(>=0.5.0), vim-plug, nodejs
- For neovim setting including coc.nvim and treesitter, copy `nvim` to `$HOME/.config` and then run `:PlugInstall` and `:CocInstall coc-pyright` in neovim.
- To easily manage dotfiles in `$HOME`, run `git --git-dir=$HOME/terminal-config --work-tree=$HOME reset --hard HEAD`
