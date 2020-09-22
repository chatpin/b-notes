Mon 21 Sep 2020 10:35:23 BST

# dotfiles/git-bare-repo

_____

## resources

> [managing dotfiles](https://news.ycombinator.com/item?id=11070797) -- original article up up on 'hacker news'

> [The best way to store your dotfiles: A bare Git repository](https://www.atlassian.com/git/tutorials/dotfiles)

> [Dot file](https://en.wikipedia.org/wiki/Hidden_file_and_hidden_directory) -- wiki

>[Git Bare Repository - A Better Way To Manage Dotfiles](https://youtu.be/tBoLDpTWVOM)

___

## notes

> making your own git bare repository  
> First, make a directory for your new git bare repository (I created one called "dotfiles" but you can name it whatever).

> Then I entered the following in the terminal:

> git init --bare $HOME/dotfiles
> alias config='/usr/bin/git --git-dir=$HOME/dotfiles/ --work-tree=$HOME' (add this alias to .bashrc)
> bash
> config config --local status.showUntrackedFiles no

> Basic usage example:

> config add /path/to/file
> config commit -m "A short message"
> config push

___

[home](/home/pi/Documents/notesystem/home.md) 

