su betty changes the user to betty
whoami prints the effective username of the current user
groups prints all the groups the user is a part of
chown changes the owner of a file or dir
touch creates an empty file
chmod u+x adds execute permission to the owner of the file
chmod ug+x adds execute permission to user and group o+r gives read permission to all
together ug+x,o+r
chmod ugo+x gives execute permission to all
chmod 007 gives all permissions to other users but zero to owner and group
chmod 753 7 all to owner 5 read and execute to group 3 write and execute to other
chmod --reference=olleh hello sets the mode of hello the same as olleh automatically
chmod -R +x . adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
Regular files should not be changed.
mkdir -m 751 my_dir makes the directory with permissions by using -m
chgrp school hello changes group owner to school for the file hello
chown vincent:staff * changes the owner to vincent and the group to staff by using : between and * for all files and directories in current directory
chown -h vincent:staff _hello the same as the last one only adding -h to be able to changefor sympolic links
chown --from=guillaume betty hello change the owner of the file hello only if its current user is guillaume
telnet towel.blinkenlights.nl playes starwars episode on terminal
