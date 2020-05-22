# python_vim_snippet
    It contains more than  48051  useful  language  snippets,  contains  with all kinds of  keywords, and it's cross  reference
    

# depend on vim  bundle , you should  install vim plugins as follow 
``` bash

git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle
git clone https://github.com/garbas/vim-snipmate.git  ~/.vim/bundle/vim-snipmate/
git clone https://github.com/honza/vim-snippets.git   ~/.vim/bundle/vim-snippets/


##
##  https://github.com/garbas/vim-snipmate#installing-snipmate

cat >> ~/.vimrc <<EOF
filetype off
set rtp+=~/.vim/bundle/vundle/
call vundle#rc()
Bundle 'gmarik/vundle'

Plugin 'MarcWeber/vim-addon-mw-utils'
Plugin 'tomtom/tlib_vim'
Plugin 'garbas/vim-snipmate'
Plugin 'honza/vim-snippets'

filetype plugin indent on

EOF


#  start vim  , and   execute following  line;
    :PluginInstall
```
