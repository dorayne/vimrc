Dorayne@ItsyBitsy ~ $ cat ~/.vimrc 
" show line numbers
set number
" highlight current line
set cursorline
" search as characters are entered
set incsearch
" highlight matches
set hlsearch
" load filetype-specific indent files
filetype indent on
" highlight trailing whitespace
match ErrorMsg '\s\+$'
" manage runtime path
execute pathogen#infect()
Dorayne@ItsyBitsy ~ $ 