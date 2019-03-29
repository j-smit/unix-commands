## UNIX-commands

## Usefull Commands
- `TAB`: **complete filename or command up to the point of uniqueness**
- `CTRL-u`: **cancel whole line**
- `CTRL-c `: **cancel the processes after it has started**
- `CTRL-n`: ** go forwards in the history of commands**. You can also use the cursor down key for this.
- `exit`: **Ends your work on the UNIX system**
- `CTRL-l or clear`: **Clear the screen**
- `CTRL-z`: **Pause the currently running program**
- `CTRL-a`: **Jump back to first character in line** 
- `CTRL-e`: **Jump forward to last character in line** 

## File Commands

### List your files
- `ls`: **lists your files**
- `ls -l`: **lists your files in 'long format'**, which contains lots of useful information (exact size , owner etc).
- `ls -a`: **lists all files**, including the ones whose filenames begin in a dot, which you do not always want to see.

### Create file
- `touch <filename`: **create or update file**

### File
- `more <filename>`: **shows the first part of a file**, just as much as will fit on one screen. Just hit the space bar to see more or q to quit. You can use /pattern to search for a pattern.
- `emacs <filename>`: **is an editor that lets you create and edit a file**. See the emacs [page](http://mally.stanford.edu/~sr/computing/emacs.html).
- `mv <filename1> <filename2>`: **moves a file** (i.e. gives it a different name, or moves it into a different directory.
- `cp <filename1> <filename2>`: **copies a file**
- `rm <filename>`:  **removes a file**. 
- `rm -i <filename>`:  **removes a file but before ask for confirmation** 
- `diff <filename1> <filename2>`: **compares files, and shows where they differ**
- `wc <filename>`: **tells you how many lines, words, and characters there are in a file**
- `chmod options <filename>`: **lets you change the read, write, and execute permissions on your files.** [chmod settings](http://www.computerhope.com/unix/uchmod.htm)


### Find
- `find <filename/directory>`: **find a file or directory**
- `find . -name FILE -print`: **Find all paths containing FILE in the current directory or below it**

### File Compression
- `gzip <filename>`: **compresses files**
- `gunzip <filename>`: **uncompresses files compressed by gzip**
- `gzcat <filename>`: **look at a gzipped file without gunzip it**. same as `gunzip -c`. 
- `gzcat <filename> | lpr`: **print it directly**

### List of options commonly used

- **a (all)** — Lists all files in the directory, including hidden files (.filename). The .. and . at the top of your 
list refer to the parent directory and the current directory, respectively.
- **l (long)** — Lists details about contents, including permissions (modes), owner, group, size, creation date, 
whether the file is a link to somewhere else on the system and where its link points.
- **F (file type)** — Adds a symbol to the end of each listing. These symbols include /, to indicate a directory; @, to 
indicate a symbolic link to another file; and /*, to indicate an executable file.
- **r (reverse)** — Lists the contents of the directory in reverse sort order.
- **R (recursive)** — Lists the contents of all directories below the current directory recursively.
- **S (size)** — Sorts files by their sizes.


## Directory Commands
- `cd <directory name>`: **Go to the directory **
- `rm -r <directory name>`: **Remove a directory with files (not hidden files)**
- `rm -rf <directory name>`: **Remove a directory with all files (also hidden)**
- `open .`: **Open current directory**

## Specials
- `cp *.JPG <directory name>`: **Copy all jpg images in directory to another directory**

## Cat command
Cat(concatenate ) command is very frequently used in linux.It reads data from file and give their content as output

- `cat filename`: to view a single file
- `cat file1 file2`: to view multiple files
- `cat -n filename`: to view contents of a file preceding with line numbers
