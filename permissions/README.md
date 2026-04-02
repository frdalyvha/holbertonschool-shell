# Permissions scripts
## 0-iam_betty - switches user to betty

## 1-who_am_i - prints effective username

## 2-groups
Prints all the groups the current user is part of.

## 3-new_owner
Changes the owner of the file 'hello' to the user betty.

## 4-empty
Creates an empty file called hello.

## 5-execute
Adds execute permission to the owner of the file hello.

## 6-multiple_permissions
Adds execute permission to owner and group owner, and read permission to other users, to the file hello.

## 7-everybody
Adds execute permission to owner, group owner, and other users for the file hello.

## 7-everybody
Adds execute permission to owner, group owner, and other users for the file hello.

## 8-James_Bond
Sets permission to hello: owner none, group none, others all (rwx).

## 8-James_Bond
Sets permission to hello: owner none, group none, others all (rwx).

## 9-John_Doe
Sets the mode of hello to -rwxr-x-wx (753).

## 10-mirror_permissions
Sets the mode of hello to match the mode of olleh.

## 11-directories_permissions
Adds execute permission to all subdirectories of the current directory for owner, group, and others. Regular files unchanged.

## 12-directory_permissions
Creates a directory called my_dir with permissions 751 in the working directory.

## 13-change_group
Changes the group owner to school for the file hello.

## 14-change_owner_and_group
Changes owner to vincent and group to staff for all files and directories in the working directory.

## 15-symbolic_link_permissions
Changes owner to vincent and group to staff for the symbolic link _hello (using -h flag).
