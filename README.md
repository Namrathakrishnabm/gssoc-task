# GSSoC Linux Basic Commands Practice

In this task, I explored and practiced basic Linux commands using Ubuntu terminal.  
I learned how to navigate directories, create folders and files, view file contents, and maintain task logs.

 Commands Practiced
- `pwd`
- `ls`
- `cd`
- `mkdir`
- `touch`
- `cat`
- `cp`
- `mv`
- `rm`
- `rmdir`
- `less`
- `head`
- `tail`
- `-i,-u,-v,-c`
- `nano`
- `wc -l`
- `echo`
- `history`

 What I Did in Day1 and Day2
- Created folders and text files
- Added task logs with timestamps
- Counted lines in files
- Viewed and edited files using terminal commands
- Explored command history and file management

 Day 3 - Linux File Handling Practice


Today I practiced basic Linux file handling and text processing commands inside the `GSSOC` directory.

 Commands Practiced

- `cat`
  - Created and viewed files
- `cat > filename`
  - Added content into files
- `cat >> filename`
  - Appended content to existing files
- `cat file1 file2 > outputfile`
  - Combined multiple files into a single file
- `sort`
  - Sorted file contents
- `sort < filename > outputfile`
  - Stored sorted output into another file
- `wc -l`
  - Counted number of lines in files
- Pipe operator `|`
  - Combined commands together

 Files Created
- `list1`
- `list2`
- `biglist`
- `slist`
- `gssoc-log.txt`

 Learning Outcome
- Understood Linux input/output redirection
- Practiced file creation and modification
- Learned file merging and sorting
- Learned line counting using `wc`
- Practiced Linux command chaining using pipes

 Status
 Day 3 task completed successfully

 Day 4 - Linux Wildcard and Command Practice


Today I practiced Linux wildcard patterns, directory navigation, and command documentation inside the `GSSOC` directory.

Commands Practiced

* `cd`

  * Navigated between directories
* `ls`

  * Listed files and folders
* `ls list*`

  * Displayed files starting with `list`
* `ls *list`

  * Displayed files ending with `list`
* `ls ?list`

  * Displayed files matching single-character patterns
* `ls *.c`

  * Listed all C source files
* `man wc`

  * Opened the manual page for the `wc` command
* `whatis wc`

  * Viewed a short description of the `wc` command

  * Logged task start and completion time

Files Used

* `gssoc-log.txt`
* `.c` files for wildcard practice
* `list` related files

Learning Outcome

* Learned how wildcard characters work in Linux
* Practiced file searching using patterns
* Improved directory navigation skills
* Understood how to access Linux command help pages
* Learned how to maintain task logs using terminal commands

 Status

 Day 4 task completed successfully

 Day 5 - Linux Permissions, Processes and Jobs

 Tasks Completed

 Today I learned about Linux file permissions, process management and job control commands.

 Topics Covered

 File Permissions

 - Used `ls -l` to view detailed file information.
 - Learned the permission format displayed by Linux.
 - Understood the three permission groups:
  - User (Owner)
  - Group
  - Others

 Permission Types

 - `r` - Read permission
 - `w` - Write permission
 - `x` - Execute permission

 Directory Permissions

 - Read (`r`) allows listing files in a directory.
 - Write (`w`) allows creating and deleting files in a directory.
 - Execute (`x`) allows accessing files and entering directories.

 Changing Permissions

 - Learned to use the `chmod` command to modify file and directory permissions.
 - Practiced adding and removing permissions using symbolic notation.

 Processes and Jobs

 - Used `sleep 10` to create a temporary process.
 - Used `sleep 10 &` to run a process in the background.
 - Learned job control commands:
  - `jobs` – List active jobs
  - `bg` – Resume a suspended job in the background
  - `fg %1` – Bring Job 1 to the foreground
  - `kill %1` – Terminate Job 1

 Process Information

 - Used `ps` to display running processes.
 - Learned how to terminate a process using:
  - `kill PID`

 Commands Practiced

 
 ls -l
 chmod
 sleep 10
 sleep 10 &
 jobs
 bg
 fg %1
 kill %1
 ps
 kill PID


This task helped me understand the basics of Linux terminal usage and improved my confidence in using Ubuntu for development tasks.
