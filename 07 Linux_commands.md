# LINUX COMMANDS 
# 1) Package Managment (debian-based)
|Command | Description | Example| 
|---|---|---|
|# LINUX COMMANDS
| `apt update`  | Update repo info   | `sudo apt update`         |
| `apt upgrade` | Upgrade packages   | `sudo apt upgrade`       |
| `apt install` | Install a package  | `sudo apt install nmap`   |
| `apt remove`  | Remove a package   | `sudo apt remove apache2` |

# 2) File & Directory Commands 
| Command | Description | Example |  
|-----|---|----|
|`pwd` | Show cureent directory | `pwd`|
|`ls`| List files/directories | `ls`|
|`ls -l`| Detailed listening | `ls -l`|
|`ls -a`| Show hidden files | `ls -a`|
|`cd`| Change directory | `cd /etc`|
|`cd ..`| Goup one level | `cd ..`|
|`cd ~`| Go to home directory | `cd ~`|
|`cd -`| Go to previous directory | `cd -`|
| `mkdir` | Create directory | `mkdir testdir`|
|`rmdir`| Remove empty dirctory | `rmdir testdir`|
|`rm`| Remove files/directories| `rm file.txt`,`rm -r dir/`|
| `touch`| Create empty file | `touch file1.txt`|
|`cp`| copy file/directory | `cp file1.txt file2.txt`|
|`mv`   | Move/rename file | `mv file1.txt file2.txt`|
|`find`| Search or files | `find . -name "*.sh"`|

# 3) File content Commands 
| Commands | Description | Example |
|-----|----|-----|
|`cat`| View file content | `cat file.txt`|
|`more`,`less`| View file with scroll | `less file.txt`|
|`head`| View first 10 lines | `head file.txt`|
|`tail`| View last 10 times | `tail file.txt`|
|`wc`| Word/line count| `wc -l file.txt`|
|`cut`| Extract columns | `cut -d',' -f1 file.csv`|
|`sort`| sort file lines| `sort file.txt`|
|`uniq` | Remove duplicates | `uniq file.txt`|
|`diff`| Show differences between files | `diff file1 file2`|

