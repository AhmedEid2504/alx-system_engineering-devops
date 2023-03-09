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
