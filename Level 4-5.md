
```
ssh bandit4@bandit.labs.overthewire.org -p 2220
ls -R -al
find -type f | xargs file
cd inhere
cat < -file07
```
find -type f -> Finds all the file in the directory
xargs file -> Passes the list of files to the 'file' command
xargs takes those arguments and appends them to the command.
