Fri 11 Sep 2020 09:40:50 BST
# calendar/tools

note
## adding items to the calendar display
___
The calendar file is preprocessed by the system's C preprocessor, allowing the inclusion of shared files such as holidays or meetings. For example I have a [calendar.fixtures](~/.calendar/calendar.fixtures) file containing the football fixtures for the season,

If the shared file is not referenced by a full pathname, the preprocessor searches in the current (or home) directory first, and then in the directory /etc/calendar, and finally in /usr/share/calendar. Empty lines and lines protected by the C commenting syntax (/* ... */) are ignored.


### Other calendars & cmd-line tools

cal -- simple printed monthly calendar 

ncal -- as above alternative display

remind -- *need to explore this further

when -- *need to explore this further
___
[index](./index-file.md)
[pi3rsync](/media/pi/8342-B101/pi/calstuff3)
[.calendar](~/.calendar/)
[home](./home.md) 
