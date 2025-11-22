**basics

This folder contains introductory exercises for learning shell scripting and understanding basic shell commands. Each script demonstrates the use of fundamental commands and file system navigation in Unix/Linux environments.

Files included
0-current_working_directory: Script that prints the absolute path name of the current working directory.

1-listit: Script that displays the contents list of your current directory.

2-bring_me_home: Script that changes the working directory to the user’s home directory.

3-listfiles: Script that displays current directory contents in a long format.

4-listmorefiles: Script that displays current directory contents, including hidden files, in a long format.

5-listfilesdigitonly: Script that displays only files’ information where user and group IDs are displayed as numbers.

6-firstdirectory: Script that creates a directory named my_first_directory in the current directory.

7-movethatfile: Script that moves the file betty from the current directory to my_first_directory.

8-firstdelete: Script that deletes the file betty in my_first_directory.

9-firstdirdeletion: Script that deletes the directory my_first_directory.

10-back: Script that changes the working directory to the previous one.

11-lists: Script that lists all files (even hidden ones) in the current, parent, and /boot directories in long format.

12-file_type: Script that prints the type of the file named iamafile.

13-symbolic_link: Script that creates a symbolic link named __ls__ to /bin/ls.

14-copy_html: Script that copies all HTML files from the current working directory to the parent directory, only if they don’t already exist in the parent directory or are newer.

15-lets_move: Script that moves all files beginning with an uppercase letter to the directory ./upper.

16-clean_emacs: Script that deletes all files in the current directory that end with the ~ character.

17-tree: Script that creates a multi-level directory structure: welcome/to/school.

README.md: This file.

Usage
Each file in this directory is a shell script. Before running, ensure each file has execution permissions:

bash
chmod +x <script_name>
Execute any script with:

bash
./<script_name>
Learning objectives
Get comfortable with basic shell commands and file system navigation.

Learn to create, move, and delete files and directories from the command line.

Understand permissions, symbolic links, and file types.

Automate common file system tasks with basic scripting.
