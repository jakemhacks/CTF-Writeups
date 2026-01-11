# Bandit 4
This one tells us that the flag is in the only human-readable file in a directory.

If you list the contents of this directory you will see a bunch of files.

![file list](/overthewire/Bandit/screenshots/bandit4_ss/ss1.png)

`file .\*` lists the filetypes of all files in the directory. Only one is ASCII text...

![file list 2](/overthewire/Bandit/screenshots/bandit4_ss/ss2.png)

-file07 has our flag.
