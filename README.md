# linux_commands

### ls:- list the files and directories in the current directory
### cd:- change the current directory
### cd <dir_name>:- change the <dir_name> directory
### cd ../:- one step back from the current directory
### mkdir:- create/make a new directory
### rmdir:- remove a directory
### pwd:- print the currentr working directory
### cp <file.txt> <dir_name>:- copy files on directories
### mv <file.txt> <dir_name>:- move or rename files on directories
### rm <file.txt>:- remove files on directories
### touch <file.txt>:- create a new empty file or update the timestamp of an existing file
### cat <file.txt>:- concatenate and display files
### man ls:- manual for a command
### htop:- an interactive process viewer and system monitor
### chmod <number> <file.txt>:- change the permissions of a file or directory {search chmod calculator and get the number}
### chown <new_owner> <file.txt>:- change the owner of a file or directory
### tar cf archive.tar file1 file2 file3:- create or extract compressed archive files
    {# x: extract files from an archive
    # t: list the contents of an archive
    # r: append files to an existing archive
    # z: use gzip compression
    # j: use bzip2 compression
    # cf: create file
    # xf: extract file
    tar cf archive.tar file1 file2 file3}
### gzip <file.txt>:- compress files
### gunzip <file.txt.gz>:- decompress compressed files
### shh <username@server_address>:- connect to a remote server securely
### scp <file.txt> <user@remotehost:/home/user/>:- securely copy files between system
### ping <ip_address>:- test netwrok connectivity
### ifconfig:- display or configure network interfaces
### netstat:- display network connection information
### route [options] [add/delete/show]:- view or configure network routing tables
### top:- display system resource usage and processes
### ps aux:- display information about running processes
### kill:- terminate a process
### systemctl:- control system services and settings
    {# Start the nginx service
    systemctl start nginx

    # Check the status of the nginx service
    systemctl status nginx

    # Stop the nginx service
    systemctl stop nginx}
### service apache2 start:- control system services
### useradd <user_name>:- add a new user to the system
### passwd <user_name>:- change the password for a user
### userdel <user_name>:- delete a user from the system
### su <user_name>:- switch user to become another user
### sudo:- execute a command as another user or with elevated privileges
### uptime:- display system uptime and load average
### df:- display disk space usage
### du:- display disk usage by file or directory
### sudo mount /dev/sdb1 /mnt/usb:- mount a file system
### sudo umount /mnt/usb:- unmount a file system
### date:- display or set the system date and time
### whoami:- display the current user name
### finger <user_name>:- displays all the information about user
### uname or uname -a:- display system information
### history:- display a list of previously executed commands
### echo 'text':- display text or variables to the console
### ls | tee <file.txt>:- redirect output to both a file and the console
### locate <file.txt>:- locate any file on the system
### sort <file.txt>:- sort lines of text in a file or input
### uniq <file.txt>:- remove duplicate lines from a file or input
### heat/tile <file.txt>:- display the first/last few lines of a file or input
    {#display first 10 lines
    head file.txt

    #display last 10 lines
    tail file.txt}
