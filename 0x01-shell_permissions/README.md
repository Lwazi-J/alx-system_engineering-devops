'su betty' script to switches the current user to the user betty
'whoami' script to print the effective username of the current user
'groups' script to prints all the groups the current user is part of
'chown betty hello' script to changes the owner of the file hello to the user betty
'touch hello' script to creates an empty file called hello
'chmod u+x hello' script to adds execute permission to the owner of the file hello
'chmod u+x,g+x,o+r hello' script to add execute permission to the owner and the group owner, and read permission to other users, to the file hello
'chmod ugo+x hello' Write a script to adds execution permission to the owner, the group owner and the other users, to the file hello
'chmod 007 hello' script to adds execution permission to the owner, the group owner and the other users, to the file hello
'chmod 753 hello' script to set the mode of the file hello to this:
-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
'chmod --reference=olleh hello' script to sets the mode of the file hello the same as olleh’s mode.
'chmod -R ugo+X' script to adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.

