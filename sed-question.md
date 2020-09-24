Fri 21 Aug 2020 17:50:43 BST

# sed/question

___

## resources

> [bash](./bash-index.md)

> [sed example](./sed-eg.md)
___

## notes

> ***asked*** on [stackoverflow](https://stackoverflow.com/questions/63526339/how-to-employ-sed-correctly-to-replace-all-the-white-spaces-with-hyphens-in-long)

> "I've been experiencing a wee issue in attempting to rename a batch of files. I need to insert (retrospectively) hyphens between a string of words in a group of unrelated files. I thought i would employ sed to replace the white spaces with hyphens and I arrived at this (please see below). Now this returns the correct result on the command-line, but, doesn't physically change the file name in the directory."

    $ ls 'long long long filename.txt' | sed 's/\s/-/g'    

*output*



    long-long-long-filename.txt

> ***answer***



    for f in *.txt; do mv "$f" "${f//[[:space:]]/-}"; done



> You have to actually issue a command that changes the filename; you're listing the filenames and then modify strings. It's either mv, like in the comment above, or one of two flavours of the rename command, as in the linked question.

___

[home](./home)

