"pwd" - shows what directory we are in currently

"ls" - lists whats in the current directory

(flag)"-l" - lists extra info about whats in directory

(flag)"-al" - lists all details of whats in directory

"cd" - change directory

	use of "cd" command to take us back to home directory

	use of "cd .." to take us back a step

	use of "cd -" to return back to previous directory

	can be used to move through series of folders with a "/" included

	tab key can be used to auto-complete


"mkdir" - makes directory (makes folder)

"touch" - creates file (requires extension and must be separated by _ or -)

"mv" - move a file (file we are moving and place we are moving to)

"mv (filename.extension) .." - moves file up the directory

can use "mv" to rename files by taking original file name and inserting next to it a new file name

eg: my_photo.png profile_picture.png

"cp" - copy a file (similar to mv)

(flag) "-r" - recursive

"-r" used to copy entire directory

"rm" - deleting (CAUTION!!! with this command, you could delete entire system)

Day 2:

"cat" - reads and displays contents of text file within terminal window (doesn't work for windows however)

in terms of git functionality,

"git init" - initiates git repository

.git can be removed with the "rm -rf .git" command

"nano <'filename'>" can be used to edit text files in the terminal

"ctrl + x" exit nano and prompt to save will appear

file is to be tracked for changes, need to use "git add" to track the file (git add . adds everything in the file)

"git status" to check tracking status of file

Commit our changes using git commit with a "-m" flag and "insert message here" to comment on changes made

using github, you can make a new repository and push the file into the repository from command line by pasting the code into terminal

"git log" will document all the versions that the file has undergone