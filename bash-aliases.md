Sun 30 Aug 2020 12:02:18 BST

# bash/aliases
note 
## the syntax for aliases

Syntax for bash aliases is as follows: 

alias shortcut='command'

for example:

    alias ln='ls ~/Documents/notesystem/'

(don't forget the single quote marks!)

## a selection of my bash aliases:
| command                          | description                  |
| -------------------------------  | ---------------------------- |
| cc='calendar -A 14'              | cal overview for 14 days |
| doc='cd ~/Documents/'            | cd's into my Documents dir |
| env='cd ~/environments/'         | cd's into enviroments dir |
| act='source my_env/bin/activate' | activates python env |
| ww='w3m www.duckduckgo.com'      | run w3m browser & search |
| myip='curl http://ipecho.net/plain; echo' | fetches my isp |
| wet='curl wttr.in'               | fetch 3 day weather forecast |

##### footnote

You may want to put all your additions into a seperate ~/.bash_aliases file, instead of adding them to your .bashrc.
___
[Aliases vs Functions](https://youtu.be/GaAfhO1kpUk)
[index](./index-file.md)
[home](./home.md) 
[.bash_aliases](~/.bash_aliases)
