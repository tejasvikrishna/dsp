# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

* show current working directory path = pwd
* creating a directory = mkdir
* deleting a directory = rmdir when empty and rm -rf when it has contents
* creating a file using `touch` command = touch creates a file without opening it (with a specified filename)
* deleting a file = rm
* renaming a file = mv
* listing hidden files = ls -a
* copying a file from one directory to another = mv
* changing permissiond of files and directories = chmod
* print text = echo

---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

`ls` = Lists all files and directories in PWD 
`ls -a` = ls but also displays hidden files 
`ls -l`  = ls but also shows file or directory, size, modified date and time, file or folder name and owner of file and its permissions
`ls -lh` = "ls -l" but shows sizes in human readable format 
`ls -lah` = combines "ls -l", "ls -a" and "ls -h"
`ls -t` = ls but sorts by file timestamp 
`ls -Glp` = "ls -l" but also includes a '/' at the end of directory names and also colorizes the list

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

ls -1
ls -R
ls -d
ls -n
ls -f

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

xargs is a command that takes input from the left (piped) and then run a command using parsed parts as arguments foe that command.

Example: echo 1 2 3 | xargs touch will create 3 files named 1, 2 and 3 respectively.
 

