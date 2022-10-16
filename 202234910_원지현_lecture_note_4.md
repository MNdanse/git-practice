# Open Source SW - Lab 4
##### 202234910 원지현 



<Kernel and Shell>

- kernel: Core of OS that controls and communicates with hardware resource
- Shell: Interface that allows users to communicate with kernel(bash, zsh).
Users runs applications and give commands through shell


### Shell command

- pwd: shows the current path in a hierarchical directory
- cd: change directory
- ls: list files and directories


### cd and ls -- argument
> [directory name]
> / root
> . current directory
> . . upper-level directory
> ~ home of current user
> /[directory name]: absolute path
> ./[directory name]: relative path
> . ./[directory name]: relative path


### ls
The **ls** command is used to list the contents of a directory. It is probably the most commonly used Linux command. It can be used in a number of different ways. 

| Command | Result |
| ----- | --- |
| ls | List the files in the working directory |
| ls/bin | List the files in the /bin directory (or any other directory we care to specify) |
| ls -l | List the files in the working directory in long format |
| ls -l/etc/bin | List the files in the /bin directory and the /etc directory in long format |
|ls -la . . | List all files in the parent of the working directory in long format |

### Manipulation: cp(copy files and directories)
| Command | Result |
| ----- | --- |
|cp  _file1_ _file2_ | Copies the contents of _file1_ into _file2_. If _file2_ does not exist, it is created. |
|cp -i _file1_ _file2_ | Link above however, since the "i" option is specified, if _file2_ exists, the user if prompted before it is overwritten with the contents of _file1_. |
|cp _file1_ _dir1_ | Copy the contents of _file1_ inside of directory _dir1_ |
|cp -R _dir1_ _dir2_ | Copy the contents of the directory _dir1_. If directory _dir2_ does not exist, it is created. Otherwise, it creates a directory named _dir1_ within directory _dir2_. |

### Manipulation: mv(move files and directories or rename them)
| Command | Result |
| ----- | --- |
|mv  _file1_ _file2_ | If _file2_ does not exist, then _file1_ is rename _file2_. If _file2_ exists, its contents are silently replaced with the contents of _file1_ |
|mv -i _file1_ _file2_ | Link above however, since the "i" option is specified, if _file2_ exists, the user if prompted before it is overwritten with the contents of _file1_. |
|mv _file1_ _file2_ _dir1_ | The files _file1_ and _file2_ are moved to directory _dir1_. If _dir1_ does not exist, *mv* will exit with an error. |
|mv _dir1_ _dir2_ | If _dir2_ does not exist, then _dir1_ is renamed _dir2_. If _dir2_ exists, the directory _dir1_ is moved within directory _dir2_.|

### Manipulation: rm(delete files and directories permantely and irreversevely)
| Command | Result |
| ----- | --- |
|rm  _file1_ _file2_ | Delete _file1_ _file2_. |
|rm -i _file1_ _file2_ | Link above however, since the "i" option is specified, the user is prompted before each file is deleted. |
|rm _dir1_ _dir2_ | Directories _dir1_ and _dir2_ are deleted along with all of their contents. |




