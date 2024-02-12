#internsctl(1) User Commands internsctl(1)

##NAME
internsctl - custom Linux command for operations

##SYNOPSIS
internsctl [OPTIONS] COMMAND [ARGS]

##DESCRIPTION
internsctl is a custom Linux command for performing various operations.

##OPTIONS
--help, -h
##Display this help message

       --version
              Display the version of the command

##COMMANDS
cpu Retrieve CPU information
memory Retrieve memory information
user Manage users
file Manage files

##EXAMPLES
internsctl cpu getinfo
Retrieve CPU information

       internsctl memory getinfo
              Retrieve memory information

       internsctl user create <username>
              Create a new user

       internsctl user list
              List all regular users

       internsctl user list --sudo-only
              List all users with sudo permissions

       internsctl file getinfo <filename>
              Retrieve information about a file

       internsctl file getinfo --size <filename>
              Retrieve the size of a file

       internsctl file getinfo --permissions <filename>
              Retrieve the permissions of a file

       internsctl file getinfo --owner <filename>
              Retrieve the owner of a file

       internsctl file getinfo --last-modified <filename>
              Retrieve the last modified time of a file

##SEE ALSO
ls(1), lscpu(1), free(1), useradd(8), userdel(8), stat(1)

##AUTHOR
Written by [Your Name]

##REPORTING BUGS
Report bugs to [Your Email]

##COPYRIGHT
Copyright © [Year] [Your Name]. License GPLv3+: GNU GPL version 3 or later
<http://gnu.org/licenses/gpl.html>.
This is free software: you are free to change and redistribute it. There is NO
WARRANTY, to the extent permitted by law.

       The full documentation for internsctl is maintained as a Markdown file.
       If you find any bugs or have a feature request, please open an issue on the GitHub repository.
