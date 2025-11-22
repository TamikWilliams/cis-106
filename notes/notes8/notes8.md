## Notes8

## cat 
  command is used for displaying the content of a file.
  cat + option + File(s) to display
  ## Basic Examples:
  ## Display the content of a file located in ~/Documents/sample_files/
cat ~/Documents/sample_files/Code/helloWorld.py
## Display the content of a file with line numbers
cat -n ~/Documents/sample_files/Code/helloWorld.py
## Display the content of a file including non printing characrers and line endings.
cat -A ~/Documents/sample_files/Code/helloWorld.py

## tac command is used for displaying the content of a file in reverse order 

tac + option + file(s) to display
## Basic Example
## Display the content of a file located in ~/Documents/sample_files in reverse order
tac ~/Documents/sample_files/Code/helloWorld.py
## Display the content of multiple files in reverser order
    ~/Documents/sample_files/Code/helloWorld.py
    /Documents/sample_files/Code/helloWorld.py.sh

## head command displays the top N of lines of a given file. By default, it prints the first 10 lines. If more than one file name is provided then data from each file is preceded by its file name.
head + option +file(s)

## Basic Example 
## Display the first 10 lines of a file 
head ~/Document/Book/dracula.txt

## Display the first 5 lines of a file
head -5 ~/Documents/Book/dracula.txt

## Displays the first 5 lines of multiple files
head -n 5 Txt/{dracula,war-and-peace}.txt

## Displays the first line of multiple files using wildcards
head -n 1 Csv/*.csv Code/*.py

## Displays a given number of lines of the output of a given command
 ls -l ~/cis106/ | head -n 2

 ## Displays the name of the file in the output

 head -v -n 7 Json/joke.json

 ## Displays a given number of bytes instead of lines

 head -c 50Txt/dracula.txt



 ## tail command displays the last N number of the lines of a given file. By default, it prints the last 10 lines. If more than one file name is provided then data from each file is preceeded by its file name.

tail + option + file(s) 
## Basic Example:
##  Displays the last 10 lines of a file
tail ~/Documents/sample_files/ 
## displays the last 5 lines of a file
tail -5 /Documents/sample_files/ 

## Displays the first 5 lines of multiple files
tail -n 5 Txt/{dracula,war-and-peace}.txt

## Displays the first line of multiple files using wildcards
tail -n 1 Csv/*.csv Code/*.py

## Displays a given number of lines of the output of a given command
ls -l ~/cis106/ | tail -n 2

## Displays the name of the file in the output
tail -v n 7 Json/joke.json

## Display a given number of bytes instead of lines
tail -c 50 Txt/dracula.txt

## cut  + optioN + file(s)
## Basic Example 
## Display a list of all the users in your system 
cut -d ':' -fl /etc/passwd

## Displays a list of all the users in your system with their login shell

cut -d ':" -fl,7 /etc/passwd
## Cut a range of bytes per line 
cut -b 1-5 usernames.txt

cut -d ':' -f1,7 --output-delimiter=' " /etc/passwd
## Cut a file excluding a given field
cut -d ',' -- complement -s -f3 users.txt
## Cut the permissions from the output of Is
ls -l | cut -d ' ' -- complement -s -f1
## sort 
## Sort a file and save the output to a new file
sort -o sorted.lst users.lst
## Sort a file in reverse order
sort -r users.txt
## Sort by column number
sort -k 2 users.txt
## Sort a file with numeric data 
sort -n codes.lst
## Check if a file is sorted 
sort -c sorted.lst
## sort and remove duplicate entries
sort -u users.lst

## wc command is used for printing the number of lines, characters and bytes in a file
wc + option + file(s)
## Basic Example
## Display the number of characters in a file 
wc -m users.txt
## Displays the number of lines in a file
wc -l users.txt
## Display the number words in a file
wc -w users.txt