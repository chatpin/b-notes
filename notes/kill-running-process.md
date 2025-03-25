Thu 15 Oct 2020 16:33:20 BST

# kill/running processes

If you are not aware of the PID \(process identifier) of the application simply run the command ps ux 

| command | option          | description                                 |
| ------- | --------------- | ------------------------------------------- |
| kill    | -9 PID          | kills that instance of running processes    |
| killall | process name    | kills all instances of process with same name |
| pkill   | application     | kills apps by their process names instead of PID |
| pkill   | -TERM pro name  | the equiv of clicking on the close button | 
| pgrep   | -l process name | lists matching process, to avoid killing |
|         |                 | the wrong process                        |
___
[index](./index-file.md)
[home](./home.md) 
