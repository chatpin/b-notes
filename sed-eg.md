Fri 21 Aug 2020 10:44:02 BST

# sed/example

___

## resources

>[sed](./sed.md)

> [bash](./bash-index.md)
 
> [50 sed command examples](https://linuxhint.com/50_sed_command_examples/)

## notes

> a tool for making commandline changes to a file and across multiple files. 

> You can do things like replace the last occurrence only of a match on each line

> here 'Programming' is 's' substituded with 'scripting'

    $ sed 's/\(.*\)Programming/\1Scripting/' lang.txt 

> Or Replace the last match in a file with new text. see below

> in this example 'Python' is 's' substituded with 'Bash'

> ‘$’ symbol is used to match the last occurrence of the pattern.
	

    $ cat python.txt
	$ sed -e '$s/Python/Bash/' python.txt 

> Substitute text but only if some other text is not found in the string

> The following `sed` command will replace the ‘Count’ value in the line that does not contain the text, ‘CSE’. dept.txt file contains two lines that do not contain the text, ‘CSE’. So, the ‘Count‘ text will be replaced by 80 in two lines.



	CSE - Count
	EEE - Count
	Civil - Count

	$ cat dept.txt
	$ sed -i -e '/CSE/! s/Count/80/;' dept.txt 

___

[home](./home)

