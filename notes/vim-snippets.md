Wed 23 Sep 2020 15:36:04 BST

**snippets**

scripts/text invoked & dragged into your document through a shortcut

the keybinding goes into your vimrc or .vimrc and the snippet or skeleton in your ~/.vim directory

>nnoremap ,mm :.-1read $HOME/.vim/intro.md<CR>"=strftime("%c")<CR>pjA

**nnoremap** (define a new key mapping for normal mode) and continue with your shortcut/cmd, in this instance **,mm** **:-1read** is the insert line number. Then the path to snippet (which is just a .txt file) **$HOME/.vim/intro.md** the **< CR >** indicates a [carriage](https://en.wikipedia.org/wiki/Carriage_return) return. **"=strftime("%c")< CR >** inserts the date/time. The **pjA** inserts the cursor at the appropriate position to begin editing the new document/note.

___
[skeleton](./skeleton.md) 
[Michael Crosby][1] 
[Taking Advantage of Using Snippets][2] 
[index](./index-file.md)
[home](./home.md)

[1]: https://m.youtube.com/watch?v=VC_GFIMxDC0
[2]: https://youtu.be/Co4S_uJYb1o
