## few basic commands in linux
### listing items in the current directory
```bash
ls
```
to list out the content of the folder
```bash
ls - lah
```
to list out all the files and content in the folder 
- `l` for long detail format
- `a` for all files including hidden
- `h` for human readable format

### to change to the directory
```bash
cd <directory_name>
```
this will change ur current directory to mention directory

### to return to the previous directory
```bash
cd ..
```
### to go the root or home directory
```bash
cd
```
### to move to the given path
```bash
cd /home/peter/downloads
```
> change path to according to ur need

## to know ur current directory
```bash
pwd
```
## check the shell name that u are using
```bash
echo $0
```
## to check the process id of the current shell 
```bash
echo $$
```
## to check the history 
```bash
history
```
### flags
* `-c` to clear all
* `-N` to show N no of history
* `-d N` to delete history from a particular starting history no.
* `-a` saves new commands to history file on disk
* `-n` reads new commands from history file that were added by other sessions

## to create a file 
### using cat
```bash
cat >> <filename.txt>
```
### using touch
```bash
 touch <filname.txt>
```
### using text editors 
```bash
vi/vim/gedit/nano <filename>
```
> choose any of the given text editors

