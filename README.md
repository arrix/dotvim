My personal dotvim setup using [pathogen](https://github.com/tpope/vim-pathogen) and [vim-update-bundles](https://github.com/bronson/vim-update-bundles).
Installation:

    cd
    git clone git://github.com/arrix/dotvim.git ~/.vim

Create symlinks:

    ln -s ~/.vim/vimrc ~/.vimrc
    ln -s ~/.vim/gvimrc ~/.gvimrc

Switch to the `~/.vim` directory, and fetch submodules:

    cd ~/.vim
    git submodule init
    git submodule update
To update bundles

    cd ~/.vim; ./update-bundles

