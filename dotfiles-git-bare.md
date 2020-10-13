Mon 21 Sep 2020 10:35:23 BST

# git/bare-repo
note
## making your own git bare repository

Make a directory for your new git bare repository (In this example it's called dotfiles it can named whatever).

this is entered in the terminal:

git init --bare $HOME/dotfiles

this alias is added to your .bashrc

alias config='/usr/bin/git --git-dir=$HOME/dotfiles/ --work-tree=$HOME' 

bash

config config --local status.showUntrackedFiles no

## Basic usage example

config replaces the git command

config add /path/to/file

config commit -m "A short message"

config push
___
[index](./index-file.md)
[hacker news-managing dotfiles](https://news.ycombinator.com/item?id=11070797) 
[The best way to store your dotfiles](https://www.atlassian.com/git/tutorials/dotfiles)
[Git Bare Repository](https://youtu.be/tBoLDpTWVOM)
[home](./home.md) 

