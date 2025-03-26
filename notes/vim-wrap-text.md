Thu 01 Oct 2020 06:49:26 BST

# vim/wrap-long-lines
___

In Vim, you may want to format long lines, that is, wrap long lines so the
longest is, say, 80 characters.

The standard approach is to set the local 'textwidth' option, then use gq to
format the wanted lines.

> :setl tw=80 

> gggqG (in normal mode)

In the above, gggqG is gg (go to the first line) then gq (format) to G (the last line).

That works, but it also joins consecutive short lines together although it does not join lines that are separated with an empty line. For example, this text:

hello 
world

final 

would be formatted to:

hello world

final 

To wrap long lines without affecting short lines, use:

:g/./ normal gqq 

The g command executes normal gqq on each line matching . (any line with at least one character). The normal-mode gqq command then formats that line.

An alternative would be to use the par text reformatter. The following replaces each line that is 80 or more characters with the result of running par. If the buffer contains 1000 long lines, this will call par 1000 times.

:g/.\{80,\}/ .!par w70 

This need arises when you copy/paste a programming
snippet into Vim, and you want to leave the indented code alone, but format the long explanation.
___ 

[vim tips wiki](https://vim.fandom.com/wiki/Format_only_long_lines)
[index](./index-file.md)
[home](./home.md) 

