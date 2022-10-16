# Open Source SW - Lab 5
##### 202234910 원지현 



### 1. I/O Redirection - Standard Output
###### By default, standard ouput is screen.
- You can redirect output using ">" after a command to create and save the output in a file.
- Using ">>" appends output to an extising file, or create and write to a new file if it doesn't exist.

### 2. Pipelines "|"
- Pipeline feeds output of previous command to input of next command.

### 3. Backslash
- Backslash can be used to ignore line change in command, to enter a long command in multiple lines.


##### Changing Permissions
Change the permission of a file "word.txt" that only the owner can read and write, but all the others can only read it. No execution is need for all users.

### 4. Superuser
- A superuser has all system administation authority.
- Some commands need superuser's privilleges.
- Put "sudo" before the command if you are a superuser.
- Type "exit" to get out of a superuser session.

### 5. Text Editors
| Name | Description | Interface |
| --- | ----- | --- |
|vi, vim|The granddaddy of Unix text editors, _vi_ is infamous for its obtuse user interface. _vim_ is a remarkable editor and well worth taking the time to learn it.|command line|
|Emacs|_Emacs_ contains every feature ever conceived of for a text editor.(written by Richard Stallman)|command line|
|nano|_nano_ is free clone of the text deitor supplied with the __pine__ email program. _nano_ is recommended for first-time users who need a command line editor.|command line|
|gedit|_gedit_ is the editor supplied with the GNOME desktop environment. _gedit_ is easy to sue and contains enough features to be a good beginners-level editor.|graphical|
|kwrite|_kwrite_ is the "advanced editor" supplied with KDE highlighting, a helpful feature for programmers and script writers.|graphical|
