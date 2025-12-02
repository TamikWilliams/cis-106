mkdir - is used for creating a single directory or multiple directories. To create a directory with mkdir type: mkdir plus the name of the directory. To create multiple directories. separate each directory name with a space. You can create directories in the present working directory or in a different directory using an absolute path. You can create a directory with a space in its name using the escape character(\) or by surrounding the name in quotation marks.                  
touch - is used for creating files. 
rm- removes files. to remove directory use rm with the -r option.To remove empty directories use the rmdir command. To remove non - empty directories use rm -r plus directory name or directory absolute path.
cp- copies files/directories from a source to a destination. The cp command use the same mv command.cp plus files to copy plus destination. To copy directories use the -r option. cp -r plus directory to copy plus destination.
mv - moves and renames directories. basic formula is mv plus source plus destination.Where source is the file or directory that you want to move and destination is where the directory or file is going. For renaming files/directories the formula remains the same: mv plus file/directory to rename plus new name. 
## Create a directory in the present directory
mkdir wallpapers

## Create a directory in a different using relative path
mkdir wallpapers/ocean

## Create a directory in a differnt directory using absolute path
mkdir ~/wallpapers/forest

## Create a directory with a space in the name
mkdir wallpapers/new\cars
mkdir wallpapers/'cities usa'

## Create a directory with a single quote in the name
mkdir wallpapers/"majora's mask"

## Create multiple directories
mkdir wallpapers/cars wallpapers/cities wallpapers/forest

## Create a directory with a parent directory at the same time
mkdir -p wallpapers_others/movies

## To create a file called list
touch list

## To create several files
touch list_of_cars.txt script.py names.csv

## To create a file using absolute path
touch ~/Downloads/games2.txt
 
 ## Yo create a file with a space in its name
 touch "list of foods.txt"

 ## The Rm 
 rm removes files
 rm by default does not removes directories. To remove a directory use rm with the -r option
 To remove non empty directories use the rmdir command
 To remove non empty directories use rm -r plus directory name or dilrectory absolute path

 ## Remove a file 
 rm list
## Remove a file and prompt confirmation before removal
rm -i lsit
## Remove all the files inside a directory and ask before removing more than 3 files
rm -I Downloads/games/*

## Remove an empty directory 
rmdir Downloads/game

## Remove an non empty directory 
rm -r Downloads/games
