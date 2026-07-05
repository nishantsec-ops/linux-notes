# linux-notes
My Linux learning notes and commands
#Day 1
  
  ### Topics Covered
  
- what is linux?
- Diffrence b/w Hardware and Software?
- What is Operating System?
- Types of Operating Systems
- What is Open Source?
- Linux Distributions
- Installation of VMware
- What is Virtualization?
- Debian-based Operating Systems
- Fedora based operating systems
- Red hat and RHEL
- Command Line and GUI

###Notes 
- to be updated after revision.
  ____
  This repository will be updated after every Linux class.

#Day 2

  ### Topics Covered

- Installing RHEL10 VERSION in VmWare
- Overview of VmWAre and there interface
- Command Line and Gui
- what is terminal?
- Root user and normal user
- RHEL ver10  after installing  overview.
- What is Bash?


###Notes 
- to be updated after revision.

_____


# Day 3 – Linux Basics & File Management Notes
📂 Working with Files
* ls – List Files & Directories

Displays the files and directories in the current location.

ls

* cat – Display File Content

- Shows the complete content of a file.

- cat filename

Example:

cat anaconda-ks.cfg

* head – View the Beginning of a File

By default, displays the first 10 lines.

head filename

Display only the first line:

head -n 1 filename

Display the first 2 lines:

head -n 2 filename

* tail – View the End of a File

By default, displays the last 10 lines.

tail filename

Display the last 2 lines:

tail -n 2 filename
##🔍 wc – Word Count Command

Displays the number of:

Lines
Words
Characters
wc filename

-  Useful options:

wc -l filename   # Count lines
wc -w filename   # Count words
wc -c filename   # Count characters

* 📖 less – View Large Files

Displays file content one screen at a time.

less filename

Press:

Q → Exit

* ⌨️ Tab Auto-Completion

The Tab key helps complete commands and filenames.

Press Tab once → Auto-completes if only one match exists.
Press Tab twice → Shows all possible matches.

Works for:

Commands
Files
Directories
Command arguments
 * ⚠️ Linux is Case Sensitive

These are different:

Documents
documents
DOCUMENTS

Example:

ls Documents/data
* 🔙 Using Backslash (\)

The backslash (\) is used to continue a command onto the next line, making long commands easier to read.

Example:

head -n 1 \
anaconda-ks.cfg

Another example:

cat \
anaconda-ks.cfg

Note: anaconda-ks.cfg is a file, whereas Documents and Desktop are directories.

* 🕘 Command History

View previously executed commands:

history

 - Re-run a command using its history number:

  !101

This executes command number 101.

* Managing Files with the Command Line
  
- Root Directory (/)

- The slash (/) represents the root directory, the starting point of the Linux filesystem.

* Common directories:

 - Directory	Purpose
    - /boot	Boot process files
    - /dev	Device files (hardware, partitions, RAM, etc.)
    - /etc	System configuration files
    - /home	Home directories of normal users
    - /root	Home directory of the root user
    - /run	Stores information about currently running processes
    - /tmp	Temporary files created automatically by the system (usually removed after about 10 days, depending on system configuration)
    - /usr/bin	User command binaries
    - /usr/sbin	System administration commands
    - /usr/local	Locally installed third-party software
    - /var	Variable data such as logs, cache, and website data
# Absolute vs Relative Paths
  - Absolute Path
     - Starts from the root directory (/).
     - Gives the complete path from start to end.

Example:

/home/nishant/Documents/file.txt
# Relative Path
 - Starts from the current working directory.
 - Shorter and depends on your current location.

Example:

Documents/file.txt
 
 * pwd – Present Working Directory

   - Displays your current directory.

pwd

# 📌 Quick Revision
Command	Purpose
- ls	List files and directories
- cat	Display file contents
- head	Show first 10 lines (default)
- head -n 1	Show first line
- tail	Show last 10 lines (default)
- tail -n 2	Show last 2 lines
- wc	Count lines, words, and characters
- wc -l	Count lines
- wc -w	Count words
- wc -c	Count characters
- less	View large files page by page
- history	Display command history
- !number	Re-execute a command from history
- pwd	Show current working directory

This repository will be updated after every linux class.

