Mon 21 Sep 2020 10:35:23 BST

# git/bare-repo

_____

## note

### <u>making your own git bare repository</u>  

> Make a directory for your new git bare repository (In this example it's called dotfiles it can named whatever).

> this is entered in the terminal

>> git init --bare $HOME/dotfiles

> this alias is added to your .bashrc

>> alias config='/usr/bin/git --git-dir=$HOME/dotfiles/ --work-tree=$HOME' 

> bash

>> config config --local status.showUntrackedFiles no

### <u>Basic usage example</u>

> <u>*config*****</u> replaces the git command

>> config add /path/to/file

>> config commit -m "A short message"

>> config push

> [index](./index-file.md)

> [managing dotfiles](https://news.ycombinator.com/item?id=11070797) -- original article up up on 'hacker news'

> [The best way to store your dotfiles: A bare Git repository](https://www.atlassian.com/git/tutorials/dotfiles)

>[Git Bare Repository - A Better Way To Manage Dotfiles](https://youtu.be/tBoLDpTWVOM)

> [home](./home.md) 

