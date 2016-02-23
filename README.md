My Vim config
==================
This is my vim config files forked from humiaozuzu/dot-vimrc

### Dependencies

1. Install Vim
``` bash
brew install macvim --override-system-vim  # OS X
yaourt -S gvim                             # ArchLinux
sudo apt-get install vim-gtk               # Ubuntu
```

2. Install ack and ctags
```bash
yaourt -S ack ctags                  # ArchLinux
sudo apt-get install ack-grep ctags  # Ubuntu
brew install ack ctags               # OS X
```

## Installation

1. Backup your old vim configuration files:

        mv ~/.vim ~/.vim.orig
        mv ~/.vimrc ~/.vimrc.orig

2. Clone and install this repo:

        git clone git://github.com/nladuo/dot-vimrc.git ~/.vim
        mkdir ~/.vim/colors;mv ~/.vim/molokai.vim ~/.vim/colors/
        ln -s ~/.vim/vimrc ~/.vimrc

3. Setup `Vundle`:

        git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle

4. Install bundles. Launch vim(ignore the errors and they will disappear after installing needed plugins)and run:

        :BundleInstall
