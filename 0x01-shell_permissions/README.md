0-iam_betty file switches the current user to the user betty
1-who_am_i file prints the effective username of the current user
2-group file prints all the groups of the current user is part of
3-new_owner changes the owner of the file hello to the user betty
4-empty file creates an empty file called hello
5-execute file ads execute permissions to the owner of the file
6-multiple_permissions file adds execute permissions to the owner, and the group owner and read permissions to other users to the file hello
7-everybody file adds execution permissions to the owner, the group owner and the other users to the file hello
8-James_Bond file sets the no permission at all to the owner and  group but sets all  permissions for others  
9-John_Doe file sets the mode of the file hello to -rwxr-x-wx
10-mirror_permissions file sets the mode of the file hello to -rw-rw-r-- 
11-directories_permissions file adds execute permissions to all subdirectories of the current directory for the owner, the group owner and all other users
12-directory_permissions fiel creates a directory called my_dir with permissions 751 in the working directory
13-change_group file changes the group owner to school for the file hello
100-change_owner_and_group
file changes the owner to vincent and the group owner to staff for all the files and directories in the working directory
101-symbolic_link_permissions file changes the owner and the group owner of _hello to vincent and staff respectively
102-if_only file changes the owner of the file hello to betty only if ut is owned by the user guillaume
103-Star_Wars file will play the StarWars IV epsode in the terminal
