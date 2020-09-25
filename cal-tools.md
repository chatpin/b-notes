Fri 11 Sep 2020 09:40:50 BST

# calendar/cmd-line
_____

## resources


> [pi3rsync](/media/pi/8342-B101/pi/calstuff3)

> [calendar](~/.calendar/) -- files to edit are **here** 

___

## notes

> The calendar file is preprocessed by the system's C preprocessor, allowing the inclusion of shared files such as holidays or meetings. I have a [calendar.fixtures](~/.calendar/calendar.fixtures) file containing the football fixtures for the season,

> If the shared file is not referenced by a full pathname, the preprocessor searches in the current (or home) directory first, and then in the directory /etc/calendar, and finally in /usr/share/calendar. Empty lines and lines protected by the C commenting syntax (/* ... */) are ignored.

> <u>calendar cmd-line tools</u>

> cal -- simple printed monthly calendar 

> ncal -- as above alternative display

> remind -- *need to look into this further

> when -- *need to look into this further

___

[home](./home.md) 
