## Linux Commands

<br>`ls` :- list the files and directories in the current directory<br>
<br>`cd`:- change the current directory<br>
<br>`cd <dir_name>`:- change the <dir_name> directory<br>
<br>`cd ../`:- one step back from the current directory<br>
<br>`mkdir`:- create/make a new directory<br>
<br>`rmdir`:- remove a directory<br>
<br>`pwd`:- print the currentr working directory<br>
<br>`cp <file.txt> <dir_name>`:- copy files on directories<br>
<br>`mv <file.txt> <dir_name>`:- move or rename files on directories<br>
<br>`rm <file.txt>`:- remove files on directories<br>
<br>`touch <file.txt>`:- create a new empty file or update the timestamp of an existing file<br>
<br>`cat <file.txt>`:- concatenate and display files<br>
<br>`man ls`:- manual for a command<br>
<br>`htop`:- an interactive process viewer and system monitor<br>
<br>`chmod <number> <file.txt>`:- change the permissions of a file or directory {search chmod calculator and get the number}<br> 
<br>`chown <new_owner> <file.txt>`:- change the owner of a file or directory<br>
<br>`tar cf archive.tar file1 file2 file3`:- create or extract compressed archive files<br>
    
    x: extract files from an archive
    t: list the contents of an archive
    r: append files to an existing archive
    z: use gzip compression
    j: use bzip2 compression
    cf: create file
    xf: extract file
    tar cf archive.tar file1 file2 file3
<br>`gzip <file.txt>`:- compress files<br>
<br>`gunzip <file.txt.gz>`:- decompress compressed files<br>
<br>`shh <username@server_address>`:- connect to a remote server securely<br>
<br>`scp <file.txt> <user@remotehost:/home/user/>`:- securely copy files between system<br>
<br>`ping <ip_address>`:- test netwrok connectivity<br>
<br>`ifconfig`:- display or configure network interfaces<br>
<br>`netstat`:- display network connection information<br>
<br>`route [options] [add/delete/show]`:- view or configure network routing tables<br>
<br>`top`:- display system resource usage and processes<br>
<br>`ps aux`:- display information about running processes<br>
<br>`kill`:- terminate a process<br>
<br>`systemctl`:- control system services and settings<br>
    
    Start the nginx service
    systemctl start nginx

    Check the status of the nginx service
    systemctl status nginx

    Stop the nginx service
    systemctl stop nginx

<br>`service apache2 start`:- control system services<br>
<br>`useradd <user_name>`:- add a new user to the system<br>
<br>`passwd <user_name>`:- change the password for a user<br>
<br>`userdel <user_name>`:- delete a user from the system<br>
<br>`su <user_name>`:- switch user to become another user<br>
<br>`sudo`:- execute a command as another user or with elevated privileges<br>
<br>`uptime`:- display system uptime and load average<br>
<br>`df`:- display disk space usage<br>
<br>`du`:- display disk usage by file or directory<br>
<br>`sudo mount /dev/sdb1 /mnt/usb`:- mount a file system<br>
<br>`sudo umount /mnt/usb`:- unmount a file system<br>
<br>`whoami`:- display the current user name<br>
<br>`finger <user_name>`:- displays all the information about user<br>
<br>`uname or uname -a`:- display system information<br>
<br>`history`:- display a list of previously executed commands<br>
<br> `echo 'text'`:- display text or variables to the console<br>
<br> `ls | tee <file.txt>`:- redirect output to both a file and the console<br>
<br> `locate <file.txt>`:- locate any file on the system<br>
<br> `sort <file.txt>`:- sort lines of text in a file or input<br>
<br> `uniq <file.txt>`:- remove duplicate lines from a file or input<br>
<br> `head/tail <file.txt>`:- display the first/last few lines of a file or input<br>
        
    display first 10 lines
    head file.txt

    display last 10 lines
    tail file.txt
