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
tree -L 2 /
sudo tree -L 3 /tree — Directory Structurestat — File Metadata
Copy code

stat file.txtdu -sh folder/
sudo du -xh / --max-depth=1 | sort -hdu — Disk Usagedf — Disk Free
Copy code

df -h
df -h /
Copy code

df -h /
