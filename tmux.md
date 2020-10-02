Wed 30 Sep 2020 21:53:30 BST

# tmux/terminal-manager
___
note
## tmux commands
___

| command                       | description | 
| ----------------------------- | ----------- |
| tmux ls 		        | lists current available sessions |
| tmuxnew -s my_session	        | starts a new session (named my_session) |
| ctrl-b-d 		        | detach from session |
| tmuxattach-sess -t my_session | re-attaches session (named my_session) |
| tmuxkill-sess -t my_session	| ends your session (named my_session) |
| ctrl-b-shift-$		| rename session from within tmux |
| ctrl-b-c		        | new window/buffer |
| ctrl-b-shift-%		| split the window virtically |
| ctrl-b-shift-"		| split the window horizontally |
| ctrl-b-z		        | zoom/focus on that pane |
| ctrl-b-t		        | tmuxclock |
| exit			        | closes panes/windows/session |

___

[index](./index-file.md)
[home](./home.md) 

