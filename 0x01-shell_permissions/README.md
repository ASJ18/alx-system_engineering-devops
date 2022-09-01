Shell permission commands 
0. command that switches the current user to another user- Superuser-su
1. a command that prints the effective username of the current user- whoami
2. a command that prints all the groups the current user is part of- groups
3. a command that changes the owner of a file to a user- chown
4. a command that creates an empty file- touch
5. a command that adds execute permission to the owner of a file- chmod u+x
6. a command that adds execute permission to the owner and the group owner, and read permission to other users, to a file- chmod u+x, g+x, o+r
7. a command that adds execution permission to the owner, the group owner and the other users, to a file- chmod ugo+x 
8. a command that sets the permission to a file- chmod 007
9. a command that sets the mode of a file- chmod 753
10. a command that sets the mode of a file the same as another files mode- chmod --reference
11. a command that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users- chmod -R a+X ./
12. a command that creates a directory with permissions 751 in the working directory- mkdir -m 751
13. a command that changes the group owner to a file for another file- chgrp
14. a command that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory- chown -R 
15. a command that changes the owner and the group owner of a file to vincent and staff respectively- chown -h
16. a command that changes the owner of the file hello to another file only if it is owned by the user guillaume- chown --fromguillame 
17. a command that will play the StarWars IV episode in the terminal- telnet towel.blinkenlights.nl
