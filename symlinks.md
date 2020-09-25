Sat 19 Sep 2020 20:09:15 BST

# symlinks/ln-command

_____


## resources

> [index](./index-file.md)

> [bash](./bash-index.md)

___

## notes

ln is a command-line utility for creating links between files. By default, the ln command creates hard links. To create a symbolic link, use the -s (--symbolic) option.

>> ln -s [OPTIONS] FILE LINK

> If both the FILE and LINK are given, ln will create a link from the file specified as the first argument (FILE) to the file specified as the second argument (LINK).

> Hard links cannot be created for directories and files on a different filesystem or partition.

> Unlike a hard link, a symbolic link can point to a file or a directory on a different filesystem or partition.

> attaching symlinks in Thunar: Stand on folder/file you want to make link to (highlighted) Go to Edit (in main menu) and choose Make link.

___

[home](./home.md) 

