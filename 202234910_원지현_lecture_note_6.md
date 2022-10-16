# Open Source SW - Lab 6
##### 202234910 원지현 



### 1. Changes vs Snapshots
- Changes: Storing data as chages to the base version
- Snapshots: Storing data as snapshots -> "git"

### 2. Centralized vs Distributed version control
- Centralized: Local computer Request to the Central VCS Sever, get the required version and act on the local computer. But when the central server goes down, each local computer fails to work with the Cental VCS Server.
- Distributed version control: Local computer and Server computer are same. Each local computer has a central database. Easily recover even if the central server goes down.

### 3. Git config
Git configurations are stored in three levels.
1. system level: --system option. Affects all uses and repsitories on the system(administrative).
_file: /etc/gitconfig_
2. global (user) level: --global option. Affects all repositories of a current user.
_file: ~/.config/git/config_
3. local level: --local option. Specific to the current repository.
_file: .git/gitconfig_
__Each level overrides values in the previous level: system -> global -> local__

##### $ git init
Initializing a repository in an existing directory.
##### $ git status
Checking repository status
##### $ git add [file_name]
Adding a new file to be staged(tracked)
##### $ git add .
Adding all files to be staged(tracked)
##### $ git rm --cached [file_name]
Unstaging a file
