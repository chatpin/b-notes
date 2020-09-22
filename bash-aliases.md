Sun 30 Aug 2020 12:02:18 BST

# bash/aliases

_____


## resources/

> [bash_aliases](/home/pi/.bash_aliases) -- aliases file

> [Aliases vs Functions](https://youtu.be/GaAfhO1kpUk) -- climagic

> [climagic](https://m.youtube.com/user/climagic) -- referanced on nixcasts its a valuable source re bash.
___

## notes/

> the syntax for aliases is as follows (don't forget the single quote marks!):

> alias <u>shortcut</u>=<u>'command'</u>

> <u>for example</u>:

    alias ln='ls ~/Documents/notesystem/'

___

> <u>a selection of my bash aliases:</u>

> **cc='calendar -A 14'** -- *displays cal overview for next 14 days*

> **doc='cd ~/Documents/'** -- *cd's into my Documents dir*

> **env='cd ~/environments/'** -- *cd's into enviroments dir*

>  **act='source my_env/bin/activate'** -- *activates python env*

> **ww='w3m www.duckduckgo.com'** -- opens w3m browser in search mode

> **sync='rsync -arv /home/pi/Documents/ /media/pi/8342-B101/Documents/'** -- backs up my Documents dir to memory stick, using rsync

> **myip='curl http://ipecho.net/plain; echo'** -- fetches my isp

> **con='cat ~/environments/contacts.csv | column -t -s, | less -S'** -- displays my contacts

> **re='nohup retext &'** -- *starts an instance of ReText*

> **wet='curl wttr.in'** -- *returns the weather forecast for the day*


> *You may want to put all your additions into a seperate ~/.bash_aliases file, instead of adding them the your .bashrc.

___

[home](/home/pi/Documents/notesystem/bash-index.md) 

