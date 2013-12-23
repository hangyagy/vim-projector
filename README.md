vim-projector
=============

Functions For quickly switching into a mode suitable for a Projector

From vim just call

    :Projector

Which will change colorscheme, disable spelling and 
clear search. For a Readable display on a projector screen.

Installation
--

###With [Pathogen](https://github.com/tpope/vim-pathogen)

Check out from github

    ## where ~/.vim is your vim files location
    cd ~/.vim/bundle
    git clone git://github.com/morganp/vim-projector.git

Add as git submodule

    ## where ~/.vim is your vim files location
    cd ~/.vim
    git submodule add http://github.com/morganp/vim-projector.git bundle/projector
    git add .
    git commit -m "Install projector.vim bundle as a submodule."
