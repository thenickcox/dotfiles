#Nick Cox's dot files

These are config files to set up a system the way I like it.

Vim-users will likely find useful stuff in .vimrc, and also vim/snippets.

#Installation

    git clone git://github.com/thenickcox/dotfiles ~/.dotfiles
    cd ~/.dotfiles
    rake install

  Vim plugins are managed through vundle. You'll need to install vundle to get them.

    git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle
    Run :BundleInstall in vim.
