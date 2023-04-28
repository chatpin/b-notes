Tue 25 Aug 09:57:52 BST 2020

# grep
note
## find a string of text in a file, or a file itself:

grep -Rinw ~/ -e 'string_of_words'

[grep](https://en.wikipedia.org/wiki/Grep) (command) -Rinw ([flags/switches](./grep-eg.md))  ~/ (directory)  -e (specifies the [string/pattern](https://en.wikipedia.org/wiki/String-searching_algorithm) to be searched) 'string_of_words'  (list all files containing a line with the text 'string_of_words')

Its name comes from the [ed](https://en.wikipedia.org/wiki/Ed_(text_editor)) command g/re/p (globally search for a regular expression and print matching lines), which has the same effect

___

see also [Regular expressions](https://en.wikipedia.org/wiki/Regular_expression)

![The match results of the pattern](https://upload.wikimedia.org/wikipedia/commons/thumb/2/23/The_river_effect_in_justified_text.jpg/220px-The_river_effect_in_justified_text.jpg)

The match results of the pattern

(?<=\.) {2,}(?=[A-Z])

At least two spaces are matched, but only if they occur directly after a period (.) and before an uppercase letter.

___
[grep](./grep-index.md)
[regex](./regex.md)
[sed](./sed-index.md)
[home](./home.md)
