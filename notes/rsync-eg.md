Sat 22 Aug 2020 13:23:27 BST

# rsync/back-up

**rsync** - fast, versatile, remote (and local) file-copying and back-up tool

cmd-line rsync [options] source-dir [destination] 

| options | description |
| ------- | ----------- |
| -a      | archive mode | 
| -r      | recursive   | 
| -v      | verbose     |

    rsync -arv /home/pi/Documents/ /media/pi/8342-B101/Documents/    

    rsync -arv /home/pi/environments/ /media/pi/8342-B101/environments/

____
[rsync remote](./rsync-remote.md)
[index](./index-file.md)
[home](./home.md)
