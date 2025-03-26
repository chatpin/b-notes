Wed 23 Sep 2020 12:04:22 BST

# vim/fold


#### when i was looking for a means to be able to link a group of notes, i stumbled upon this. (I seem to recall it was up on stackoverflow)

How to link to another file in vim?

"I downloaded the DrawIt plugin to draw a diagram in vim. I successfully installed that plugin. Then I found DrawIt.vba file in my home directory and opened the file. It had the following content:

"Vimball Archiver by Charles E. Campbell, Jr., Ph.D.
 UseVimball
 finish
 +-- 67 lines: plugin/DrawItPlugin.vim--------------------------------------------
 +--484 lines: plugin/cecutil.vim ------------------------------------------------
 +--1662 lines: autoload/DrawIt.vim-----------------------------------------------
 +--401 lines: doc/DrawIt.txt-----------------------------------------------------

"In that file, I placed the cursor in the + (plus) and I pressed the right arrow key(-). It opens the specified path (plugin/DrawItPlugin.vim) of the file."

"It's not a link and it doesn't open any file. It's a fold (:help usr_28, :help fold.txt) containing the entire file contents — vimball is a rather simple archive format"

"anytime you have a path in a file you can likely open that file by putting your cursor anywhere on the path and pressing gf. The file will be opened in another buffer." – Randy Morris Feb 13 

"You can "jump" to a file whose path is under cursor with gf (goto file). Type :he gf for details."

"Finally, using the "VimWiki" plugin, you can create files that link to other files, in a Wiki fashion."

___
[index](./index-file.md)
[home](./home.md)
