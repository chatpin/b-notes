Fri 21 Aug 2020 14:22:25 BST

# mv/moving-files

**moving files from one dir to another:**

	"$ mv -i [which-file] [DESTINATION]" 

**bulk move**

	"$ mv -t [DESTINATION] file1 file2 file3 "

**rename a file**


	"$ mv [oldname] [newname]"

moves the file to another directory and if the same file is already there, generate some random string that is not in the name of some file in the directory and rename the file to this random string:



    tmp=$(TMPDIR=$(dirname -- "$destination") mktemp -t)


    mv -- "$source" "$tmp"


    echo n | mv -i -- "$tmp" "$destination"

___
[index](./index-file.md)
[bash](./bash-index.md)
[home](./home.md) 

