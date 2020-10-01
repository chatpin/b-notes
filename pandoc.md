Wed 30 Sep 2020 20:57:30 BST

# pandoc/document-converter
_____

note
## pandoc commands
___

by default, input is interpreted as pandoc: markdown, and output is html.

pandoc -f html -t markdown 

(-f from) (-t to) easy to remember this way

## to convert a file:

pandoc my_file.md -f markdown -t html -s -o my_file.html

(-s = send) (-o = output)

to create a LaTex document its .tex

to create a Word document its .docx

(to create a pdf document requires the texlive pkg on Linux)
___

[index](./index-file.md)
[home](./home.md) 

