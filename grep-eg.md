Fri 21 Aug 2020 11:46:09 BST

# grep/example
notes
##To find files containing specific text

##### grep example

	'$ grep -iRl "your-text-to-find" ./'

##### the switches:
| options | result           |
| ------- | ---------------- |
| -i      | ignore text case |
| -R      | recursively search files in subdirectories |
| -l      | show file names instead of file contents portions |

./ - the last parameter is the path to the folder containing files you need to search for your text. In this case, it is the current folder with the file mask. You can change it to the full path of the folder.

### Other useful switches you can use with grep:

| options | result               |
| ------- | -------------------- |
| -n      | show the line number |
| -w      | match the whole word |

grep -Rnw --include=|*.txt ~/ 'string_of_words' instructs grep to only look through .txt files
___
[index](./index-file.md)
[grep](./grep-index.md)
[Learn Grep Command in Unix/Linux with Simple Examples](https://www.linuxteacher.com/grep-command-in-unix-linux-with-examples/)
[home](./home.md)
