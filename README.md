# My vimrc
Inspired by [The Ultimate vimrc](https://github.com/amix/vimrc)

## Installation

### [Pathogen](https://github.com/tpope/vim-pathogen)
    mkdir -p ~/.vim/autoload ~/.vim/bundle && \
    curl -LSso ~/.vim/autoload/pathogen.vim https://tpo.pe/pathogen.vim

### [Nerd Tree](https://github.com/scrooloose/nerdtree)
    cd ~/.vim/bundle && \
    git clone https://github.com/scrooloose/nerdtree.git

### [Git gutter](https://github.com/airblade/vim-gitgutter)
    cd ~/.vim/bundle && \
    git clone https://github.com/airblade/vim-gitgutter.git

## Key Mappings

Open new tab:

    , + t + n

Close tab:

    , + t + c

Next tab:

    , + t + n

Open a new tab with the current buffer's path:

    , + t + e

Switch CWD to the directory of the open buffer:

    , + c + d

Toggle paste mode on and off:

    , + p + p

Toggle NERD Tree:

    , + n + n

Toggle Git gutter:

    , + d

