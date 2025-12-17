
## ls - used for displaying all the files inside a given directory. When no directory is specified, ls 
displays the files in the current working directory.

## Examples 
## ls list the content of the present working directory
## ls -a List all the files inside the current working directory including hidden files
## ls -a ~/Pictures- 

# List all the files in a given directory recursively.
## ls -lR ~/Pictures

## man ls - to search for commnd also do grep
## similar commands
dir, tree, exa
## cd - used for changing the current working directory is given, cd changes the current user. 

## Change from your home directory to a Downloads directory. 
cd Downloads

## from anywhere in file system change to your Downloads directory
cd ~/Downloads

## from anywhere in the file system change to your Documents directory.
cd /home/$USER/Documents

## assuming that your present working directory is /usr/share/themes/ go to /usr/share
cd ../

# If you want to go to your home directory you can use the following
cd 
cd ~
cd $Home
If you want to go to the previous current working directory you can use
cd -
pwd- used for displaying the current work directory.

## what is a variable? 
is a container or placeholder for data
allows you to temporarily store information within the shell script for use with the other commands in the script.


## How do I use a variable? User="Bob" is read as
User contains the value "Bob"
User has the value "Bob"
User store the value "Bob"
User has assinged the value "Bob"


## What is an environment variable? 
are used by the shell to track specific system information
Some environment variable's value do not change from user to user, while user specific environment variable will change depending on the user logged in.
you can use any of the following commands to see a list of environment variables: env, set, printenv

## Environment varibales are typed in capital letters. This helps to differntuate them from user defined variables.

To use environment variables, type their name starting with a dollar sign 
## Example 
echo $USER will display the current user.




## What is an user defined variable? 
are created by the user and exist only in the script
and subshell that runs the script.
User variables alllows you to temporarily store and use data and use it throughout the script. 

## Rules for creaitng vaiables can be any text string of up to 20 letters, digits, or underscore characters but they CANNOT start with a number.

## User variables are case sensitive 
## Values are assigned using an equal sign no spaces (name='Peter')
 ## The shell storess all values as text strings: Bash is essentially untyped


# What the root directory?
- is the administrator of your system 

## What does "Parent Directory" mean? 
- allows you to move forward to a subdirectory

# What does "Current directory" mean? 
- the directory you are at the moment

# What is an absolute path?
- f Include an example full pathname absolute path always starts with the /home/tdw/music/song.mp3

# What is relative path? Include an example starts with a subdirectory partial pathname for example:
-  music/song.mp3

# What is the difference between " Your home directory" and 'The home directory"?
-"Your directory" is my user's  and "The home directory" is located in the root.



