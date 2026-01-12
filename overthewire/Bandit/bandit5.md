Bandit 5
This one asks for us to find a file with 3 properties:
- human readable
- 1033 bytes in size
- not executable

The `inhere/` directory has several subdirectories.

![List1](/overthewire/Bandit/screenshots/bandit5_ss/ss1.png)

If we navigate to the `inhere/` directory and use the `find -readable -size 1033c` command, the only file returned is `inhere/maybehere07/.file02`

[!flagfile](/overthewire/Bandit/screenshots/bandit5_ss/ss2.png)

This file contains our flag for level 6.
