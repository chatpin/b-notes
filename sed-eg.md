Fri 21 Aug 2020 10:44:02 BST
#sed-example
[sed](/home/pi/Documents/index.md)
 
[https://linuxhint.com/50_sed_command_examples/](https://linuxhint.com/50_sed_command_examples/)

###Sed command looks like a most useful tool for making commandline changes to a file and perhaps across multiple files. This site/article would seem like a good place to start.

You can do things like replace the last occurrence only of a match on each line! see below



> in this example 'Programming' is 's' substituded with 'scripting'

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



