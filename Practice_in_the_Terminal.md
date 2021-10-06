# Practice in the Terminal

### The Command Line 

- What is it, how does it work and how do I get to one.

**The command lin is :**
A text-based user interface to the computer, and it is a blank line and cursor on the screen, allowing the user to type in instructions for immediate execution

**How it work:**
that forwards commands from the user to the operating system

**how do I get to one:**
it is embeded in your OS 

### Basic Navigation - An introduction to the Linux directory system and how to get around it.

1. To navigate into the root directory, use "cd /".

2. To navigate to your home directory, use "cd" or "cd ~"
3. To navigate up one directory level, use "cd .."
4. To navigate to the previous directory (or back), use "cd -"

### More About Files - Find out some interesting characteristics of files and directories in a Linux environment.

**in the linux** evrything is file like: text file,dircktory,image, your keybord and ...etc

**Linux is case sensitive**
* Beware of silly typos.


**Manual Pages**

`The manual pages are a set of pages that explain every command available on your system including what they do`

if you want to do an action and you dont know what is the command that can do this action u can write in  your terminal `man -k <search term>`


### File Manipulation 

1. to craete a directory : `mkdir <name>`
2. `mkdir -p` : which tells mkdir to make parent directories as needed
3. `mkdir -v`: which makes mkdir tell us what it is doing
4. removing a directory : `rmdir [options] <Directory>`
5. creating a file :`touch <name>`
6. Copying a File or Directory: `cp [options] <source> <destination>`
7. moving a File or Directory: `mv [options] <source> <destination>`
7. renaming a file :`mv <last name> <new name> `
8. Removing a empty File :`rm <name>`
8.  Removing a nonempty File :`rm -r <name>`