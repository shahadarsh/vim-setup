# vim
Repository for Vim setup

### Setup vim 

```$ git clone git@github.com:shahadarsh/vim-setup.git ~/.vim
$ vim ~/.vim/vimrc
# Wait for vim-plug to install all plugins
$ cd ~/.vim/plugged/YouCompleteMe/
$ brew unlink python #If using maci as per this: https://github.com/Valloric/YouCompleteMe/issues/8#issuecomment-20942923
$ ./install.sh --clang-complete
$ brew link python #If using mac
# Wait for YouCompleteMe to compile```
