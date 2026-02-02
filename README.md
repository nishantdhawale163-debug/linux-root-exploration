# linux-root-exploration
Linux filesystem practice for SRE
MD 
# project Name
Short description.
## Objectives
## Topics covered
## Step-by-step Lab
## How to Run
## Future Additions
/ — Root Directory
Top-level of filesystem
Everything exists under /
/home
User home folders
Personal files live here
/etc
Configuration files
System behavior controlled here/var
Frequently changing files
Logs, cache, spool
/proc
Virtual filesystem
Kernel + process info
/tmp
Temporary working directory
Usually cleared after rebootpwd
Prints current path.
Copy code

pwd
cd
Changes directory.
Copy code

cd /
cd /home
cd ..
cd ~ls
Lists files.
Copy code

ls
ls -l
ls -a
ls -lh
tree
Shows folder structure.
Copy code

sudo apt install tree
tree -L 2 /stat
Displays file metadata.
Copy code

stat file.txt
du
Shows disk usage.
Copy code

du -sh folder/df
Shows free disk space.
Copy code

df -h /
