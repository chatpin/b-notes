Thu 24 Sep 2020 14:12:33 BST

# some stuff in my vimrc

___

> [vimrc](/etc/vim/vimrc)

___

## all pretty much vanilla

> runtime! debian.vim

> **" the below line prevents defaults.vim from being loaded**

> let g:skip_defaults_vim = 1

> colo evening

> syntax on

> set background=dark

> **" Vim jumps to the last position when reopening a file**

> au BufReadPost * if line("'\"") > 1 && line("'\"") <= line("$") | exe "normal! g'\"" | endif

> filetype plugin indent on

> let g:netrw_liststyles= 3


> set showcmd		**" Show (partial) command in status line.**

> set showmatch		**" Show matching brackets.**

> set ignorecase		**" Do case insensitive matching**

> set smartcase		**" Do smart case matching**

> set incsearch		**" Incremental search**

> set autowrite		**" Automatically save before commands like :next and :make**

> set hidden		**" Hide buffers when they are abandoned**

> set mouse=a		**" Enable mouse usage (all modes)**

> set number

> set path+=**

> set wildmenu

> set dictionary=/usr/share/dict/words

> set complete+=k

> set foldmethod=manual	**" enabling vim folds**

" **some keybindings for my snippets**

> nnoremap ,mm :.-1read $HOME/.vim/intro.md<CR>"=strftime("%c")<CR>pjA

> nnoremap ,d "=strftime("%c")<CR>po

> nnoremap ,h :.-1read $HOME/.vim/home.md<CR> 



> **" Source a global configuration file if available**

> if filereadable("/etc/vim/vimrc.local")

>> source /etc/vim/vimrc.local
  
> endif

___

[home](./home.md) 

