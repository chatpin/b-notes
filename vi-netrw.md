
vi-netrw

Vim: you don't need NERDtree or (maybe) netrw
https://shapeshed.com/vim-netrw/


Invoking netrw can be achieved in three ways

    		:Explore - opens netrw in the current window
    		:Sexplore - opens netrw in a horizontal split
    		:Vexplore - opens netrw in a vertical split

There are four different view types: thin, long, wide and tree.
With the directory browser open hit i to cycle through the view types.
A preferred view type can be made permanent by setting it in a .vimrc file.

		let g:netrw_liststyle = 3

