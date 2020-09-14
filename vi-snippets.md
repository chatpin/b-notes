
#vi/snippets

scripts/text invoked & dragged into your document through a shortcut
____

resources

###local/

* [intro.md](/home/pi/.vim/intro.md) -- (local link) skeleton (or template) of a note 

* [skeleton](/home/pi/Documents/notesystem/skeleton.md) -- sample

###web/
  * [Michael Crosby][1] -- thanks to Michael Crosby for the insight
  * [Taking Advantage of Using Snippets][2] -- Nick Janetakis youtube tutorial
_____
**notes**/

    nnoremap ,mm :.-1read $HOME/.vim/intro.md<CR>"=strftime("%c")<CR>pjA

> **nnoremap** (define a new key mapping for normal mode) and continue with your shortcut/cmd, in this instance **,mm** **:-1read** is the insert line number. Then the path to snippet (which is just a .txt file) **$HOME/.vim/intro.md** the **< CR >** indicates a [carriage](https://en.wikipedia.org/wiki/Carriage_return) return. **"=strftime("%c")< CR >** inserts the date/time. The **pjA** inserts the cursor at the appropriate position to begin editing the new document/note.

[home](/home/pi/Documents/notesystem/vim-index.md)

[1]: https://m.youtube.com/watch?v=VC_GFIMxDC0
[2]: https://youtu.be/Co4S_uJYb1o