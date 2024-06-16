This script switches the current user to the user betty. It contains the following lines:
- #!/bin/bash : Specifies that the script should be run in the Bash shell.
- su betty : Command to switch the current user to betty.
- whoami : This script prints the effective username of the current user.
- touch hello : This script creates an empty file called hello.
- chmod u+x hello : This script adds execute permission to the owner of the file hello.
- chmod u+x,g+x,o+r hello : This script adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
- chmod 753 hello : This script sets the mode of the file hello to -rwxr-x-wx.
