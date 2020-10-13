Wed 23 Sep 2020 14:04:17 BST

# vim/netrw
note
## vim's built in finder
Invoking netrw, vim's built in finder, can be achieved in a nuber of ways:

| command   | description                        |
| --------- | ---------------------------------- |
|:edit.     | opens netrw in new buffer          |
|:Explore   | opens netrw in the current window  |
|:Sexplore  | opens netrw in a horizontal split  |
|:Vexplore  | opens netrw in a vertical split    |

There are four different view types: thin, long, wide and tree.
With the directory browser open hit i to cycle through the view types.
A preferred view type can be made permanent by setting it in a .vimrc file.

let g:netrw_liststyle = 3

___
[Vim: you don't need NERDtree or (maybe) netrw](https://shapeshed.com/vim-netrw/)
[vim index](./vi-index.md)
[index](./index-file.md)
[home](./home.md)
