Fri 21 Aug 2020 11:46:09 BST

# grep/example

another grep example

___

## resources

> [grep](/home/pi/Documents/notesystem/grep-index.md)

> [Learn Grep Command in Unix/Linux with Simple Examples](https://www.linuxteacher.com/grep-command-in-unix-linux-with-examples/)

___

## notes

> To find files containing specific text:

	'$ grep -iRl "your-text-to-find" ./'

> Here are the switches:

> -i - ignore text case

> -R - recursively search files in subdirectories.

> -l - show file names instead of file contents portions.



> ./ - the last parameter is the path to the folder containing files you need to search for your text. In our case, it is the current folder with the file mask. You can change it to the full path of the folder.

> Other useful switches you can use with grep:

> -n - show the line number

> -w - match the whole word.

> grep -Rnw --include=|*.txt ~/ 'string_of_words'

> instructs grep to only look through .txt files

___

[home](/home/pi/Documents/notesystem/home.md)
