# linux-nvim
My init file for neovim on linux.

You'll need to download FZF into the correct directory, and install ripgrep:
```
sudo apt-get install ripgrep
curl -fLo ~/.var/app/io.neovim.nvim/data/nvim/site/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```
Close nvim (and maybe that terminal) and then open and type this:
```
:PlugInstall
```

Links to more info:
https://github.com/junegunn/vim-plug
https://github.com/junegunn/fzf#installation
