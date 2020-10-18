# srm
 ## Command description
 The srm command was created for careful file deletion, files and directories are deleted by the `srm file name` command,
 after executing the command, the script checks if the ~/RECYCLE directory exists, if not, it creates it,
 then the files are moved to the ~/RECYCLE directory, then automatically compressed with the gzip command,
 then the command checks for old files in the directory deleted 7 days ago,
 if there are any, then in ~/RECYCLE all files and directories deleted 7 days ago are deleted.

 # Command setup

 - Download the srm file to your home directory
 - Run the command `mkdir ~/bin`
 - Then execute `echo export PATH="${PATH}:~/bin" >> ~/.bash_profile`
 - Next, move the previously downloaded srm file to the bin directory, you can do this with the command `mv ~/srm ~/bin`
 - Run the command `chmod +x ~/bin/srm`
 - Reconnect to server

 Everything is ready! You can use
