
   ## What is a graphical user interface (GUI)? a graphical user interface is a of program that allows a user to with a computer system via icons window and various other virtual elements.
   ## What is a desktop environment? is an implementation of the desktop metaphor made ofa bundle of programs running on top of a computer operating system which shares a common GUI sometimes described aa a graphical shell.
## is the command line interface (CLI)? the user interacts with the computer by inputting commands, the commands are interpreted by a shell, the shell can be considered a programming language
   ## How do I access the command line interface (CLI)? Terminal Emulator and Linux console
   ## What is a virtual console? a terminal system that runs in Linux system memory.
   ## What is a terminal emulator? allows you to access Linux CLI when using the GUI
  ##  What is bash? a program that provides interactive access to the Linux system
## What is the shell prompt? When you launch a terminal

# Definition, usage, and examples of the following commands:

  ## clear clears the terminal window/screen
  ## echo Prints/displays text to screen
   - date displays current date and time
   - free Displays the amount of RAM/ memory used and free
   - uname sgiws basic information about your system such as Kernel, OS, architecture
  - history display a history of every command you run so farPrints/displays text to screen
 -  man Shows/displays manual page for a given command
  - tldr similar to cheat sheet but it is available to APT and keeps the local cache
    cheat a collection of cheat sheets
    hostname Shows the system's hostname 
 -  df Displays the amount of disk space available/used on entire file systems/partitions
    - du dispalys the amount of space used by specific files or directories 
    figlet displays text in ASCII letters

## echo plus option plus string


Display/print a line of text to the screen
## echo "Hello World"

Display/print 2 lines of text to the screen in a single echo command

## echo -e "line1\nLine2"

Displays/print a line of text to the screen supressing the new line
## echo -n "Hello World"

Display/print a line of text to the screen with a tab

## echo -e "\tHello World"

  ## -n Do not append a newline at the end of the output.  ex. echo -n "Hello"

  ## -e Enable interpretation of backlash escapes (like \n,\t,etc)


  ## echo -E "Hello\nWorld

## -E Disable interpretation of backlash escapes (this is the default behavior)

## echo -E "Hello\nWorld"

## Escape Sequence    Meaning 
 ## -e Enable interpretation of backlash escapes (like \n,\t,etc) (use -e after echo to perform the followig commands)
     Example Output
\n                    Newline     Hello\nWorld
\t                    Horizontal tab  Hello\tWorld
\\                    Backlash    Hello\\World
\b                    Backspace   Hello\bWorld
\a                    Alert (bell) Triggers sound alert

`echo -e "line1\nline2" `

``` bash
echo "Current date UTC"
date -u
echo "Disk space human readable -h"
df -h
echo "memory"
free -h
echo "hostname"
uname -n
echo "operating system"
uname -op
```
  #  example

    echo: to display text
    date: to manipulate dates
    df: disk space usage
    free: memory usage
    uname: basic system information
    clear: clear screen
