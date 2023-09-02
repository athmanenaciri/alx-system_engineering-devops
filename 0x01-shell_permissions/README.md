# 0x01 Shell Permissions

This repository contains shell scripts that perform various tasks related to file permissions.

## Tasks

### 0-iam_betty

This script switches the current user to the user betty. It uses exactly 8 characters for the command.

### 1-who_am_i

This script prints the effective username of the current user.

### 2-groups

This script prints all the groups the current user is part of.

### 3-new_owner

This script changes the owner of the file hello to the user betty.

### 4-empty

This script creates an empty file called hello.

### 5-execute

This script adds execute permission to the owner of the file hello.

### 6-multiple_permissions

This script adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.

### 7-everybody

This script adds execution permission to the owner, the group owner, and other users, to the file hello.

### 8-James_Bond

This script sets the permission to the file hello as follows:

- Owner: no permission at all
- Group: no permission at all
- Other users: all the permissions

### 9-John_Doe

This script sets the mode of the file hello to -rwxr-x-wx.

### 10-mirror_permissions

This script sets the mode of the file hello the same as olleh's mode. It works for any mode of olleh.

### 11-directories_permissions

This script adds execute permission to all subdirectories of the current directory for the owner, the group owner, and all other users. Regular files are not changed.

### 12-directory_permissions

This script creates a directory called my_dir with permissions 751 in the working directory.

### 13-change_group

This script changes the group owner to school for the file hello.

### 14- Owner and group (Advanced)

Write a script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.

### 15- Symbolic links (Advanced)

Write a script that changes the owner and the group owner of _hello to vincent and staff respectively. The file _hello is in the working directory, and it is a symbolic link.

### 16- If only (Advanced)

Write a script that changes the owner of the file hello to betty only if it is owned by the user guillaume.

### 17- Star Wars (Advanced)

Write a script that will play the StarWars IV episode in the terminal.

