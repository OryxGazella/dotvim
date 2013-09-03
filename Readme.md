#Installation: #

## Clone ##
    git clone git://github.com/oryxgazella/dotvim.git ~/.vim

## Create symlinks: ##

    ln -s ~/.vim/vimrc ~/.vimrc


## Update submodules ##

    cd ~/.vim
    git submodule init
    git submodule update

## Command-T ##

You might have to change the makefile with the following.

    -CFLAGS += -std=c99 -Wall -Wextra -Wno-unused-parameter
    +CFLAGS += -std=gnu99 -Wall -Wextra -Wno-unused-parameter -lpthread

# Sources #

* Adapted from Drew Neil's dotvim [repository](https://github.com/nelstrom/dotvim)
and [podcast](http://vimcasts.org/episodes/synchronizing-plugins-with-git-submodules-and-pathogen/).
* VimCasts Ep 1 - [Show Invisibles](http://vimcasts.org/episodes/show-invisibles/)
* Skittles Berry colorscheme by [Shawn Biddle](https://github.com/shawncplus/skittles_berry)
