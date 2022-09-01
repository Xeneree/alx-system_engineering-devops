#!SHELL_PERMISSION_DESCRIPTION
TASK  0:The script switches the current user to the user betty. $ "su betty"

TASK  1:The script that prints the effective username of the current user. $ "id -un" 

TASK  2:The script prints all the groups the current user is part of. $ "id -Gn" 

TASK  3:The function of the script is that it changes the owner of the file to current user. betty becomes the new owner of the hello file. $ "chown betty hello"

TASK  4:$ "touch hello" creates an empty file (hello).

TASK  5:Adds execute permission to the owner of the file hello. $ "chmod u+x hello"

TASK  6:The command line  $ "chmod ug+x,o+r hello" grants groups and owner the execute permission and other users read permission to the (hello file).

TASK  7:$ "chmod ugo+x hello", this command line add execution permission to all for file (hello).

TASK  8:$ "chmod 007 hello" Create the file with the permissions set so that other users have full access and the owner and group have no access.

TASK  9:The script grants permissions so the owner has all permissions, while group has read and execute permissions and others have write and execute permissions.

TASK 10:$ "chmod --reference=olleh hello" This script copies the mode of file olleh to the file (hello).

TASK 11:The $ "chmod -R +X" add execute privileges for everyone to the current directory's subdirectories. Ordinary files should not be modified.

TASK 12:The script with $ "mkdir -m 751 my_dir" in the working directory, makes a directory with the name "my_dir" with the permissions 751. The user is granted full read, write, and execute rights.while group is granted read and execute rights. Others only have the authority to execute.

TASK 13:$ "chgrp school hello" the command line in the script changes the gorup owner to (school) for the file (hello).

TASK 14:$ "chown betty:school * " Change owner to betty and the group owner to school for all files and directories in current directory.
