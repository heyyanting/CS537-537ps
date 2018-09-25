# Project 1: 537ps

## Features
* -p <pid>
    Display process information only for the process whose number is pid. If this option is not present then display information for all processes of the current user.
* -s
    Display the single-character state information about the process. This information is found in the stat file in process's directory, looking at the third ("state") field. Note that the information that you read from the stat file is a character string. This option defaults to be false, so if it is not present, do not display this information. -s- is valid but has no effect.
* -U
    Display the amount of user time consumed by this process. This information is found in the stat file in process's directory, looking at the "utime" field. This option defaults to be true, so if it is not present, then this information is displayed. -U- turns this option off.
* -S
    Display the amount of system time consumed so far by this process. This information is found in the stat file in process's directory, looking at the "stime" field. This option defaults to be false, so if it is not present, then this information is not displayed. -S- is valid but has no effect.
* -v
    Display the amount of virtual memory currently being used (in pages) by this program. This information is found in the statm file in process's directory, looking at first ("size") field. This option defaults to be false, so if it is not present, then this information is not displayed. -v- is valid but has no effect.
* -c
    Display the command-line that started this program. This information is found in the cmdline file in process's directory. Be careful on this one, because this file contains a list of null (zero byte) terminated strings. This option defaults to be true, so if it is not present, then this information is displayed. -c- turns this option off.

## Functions

