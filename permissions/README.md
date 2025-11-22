**permissions

This folder contains shell scripts for practicing and understanding file and directory permissions, ownership, and group management in Unix/Linux systems. The exercises develop skills related to reading, modifying, and managing file permissions and attributes from the command line.

Files included
0-iam_betty: Script that changes your user ID to betty.

1-who_am_i: Script that prints the effective username of the current user.

2-groups: Script that prints all the groups a user belongs to.

3-new_owner: Script that changes the owner of the file hello to betty.

4-empty: Script that creates an empty file called hello.

5-execute: Script that adds execute permission to the owner of the file hello.

6-multiple_permissions: Script that adds write permission to the owner, execute permission to group, and read permission to others for the file hello.

7-everybody: Script that adds execute permission to the owner, group, and others for the file hello.

8-James_Bond: Script that sets the permissions of the file hello to 007.

9-John_Doe: Script that sets the mode of the file hello to 753.

10-mirror_permissions: Script that sets the mode of the file hello the same as the file olleh.

11-directories_permissions: Script that adds execute permission to all subdirectories of the current directory for the owner, group, and others.

12-directory_permissions: Script that creates a new directory called my_dir with permissions 751.

13-change_group: Script that changes the group owner of the file hello to school.

14-change_owner_and_group: Script that changes the owner to vincent and the group to school for the file hello.

15-symbolic_link_permissions: Script that changes the mode of the symbolic link hello to 777.

16-if_only: Script that changes owner of the file hello to guillaume only if it is owned by vincent.

README.md: This file.

Usage
All files are shell scripts. Before running, grant execution permission:

bash
chmod +x <script_name>
Run a script with:

bash
./<script_name>
Learning objectives
Read and interpret file permissions using ls -l.

Change file and directory ownership and group using chown and chgrp.

Modify permissions using chmod with numeric and symbolic modes.

Understand user, group, and other permissions, and manage executable, readable, and writable modes.
