# Nvim as Python / Rust / any another language IDE!

Video (in Russian) — https://www.youtube.com/watch?v=PA7zZNJXJEk

For Mac OS:

```sh
brew install nvim
brew install rust-analyzer
brew install ripgrep
npm install -g pyright
```

For Manjaro Linux:

```sh
sudo pacman -S nvim
sudo pacman -S rust-analyzer
sudo pacman -S ripgrep
sudo pacman -S pyright
```

Install also [vim-plug](https://github.com/junegunn/vim-plug) — plugin manager for vim/nvim.

Put [init.vim](init.vim) to `~/.config/nvim/init.vim` folder.
Further when editing the `init.vim` file you need to install all plugins `:PlugInstall` and after installation `:so %` to reread the config file.
