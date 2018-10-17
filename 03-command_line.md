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

> > * show currently working directory path = pwd
> > * creating a directory: mkdir
> > * deleting a directory: rmdir
> > * creating a file: touch _filename_
> > * deleting a file: rm _filename_
> > * renaming a file: mv _oldfilename_ _newfilename_
> > * listing hidden files: ls
> > * copying a file between directories: cp _filename_ /_newdirectory_

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

> > 'ls' : lists all files/directories
> > 'ls -a' : lists hidden files/directories
> > 'ls -l' : lists long format for files/directories
> > 'ls -lh' : lists long format in human readable form
> > 'ls -lah' : 
> > 'ls -t' : lists by time/date (most recent at top)
> > 'ls -Glp' :  

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > 'ls -R' : displays subdirectories
> > 'ls -u' : displays files by access time
> > 'ls -1' : displays 1 entry/line
> > 'ls -x' : displays files as rows across screen
> > 'ls -d' : displays only directories

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > xargs is a tool that reads data from standard input and exectures the supplied command. For example:

> xargs find -name
> "*.png"
>prints out all .png files in working directory
 

