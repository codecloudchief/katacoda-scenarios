In Linux operating system you should know the directory where you are and as what user you have logged in to the system.

These two determines what level of access you have been provided, for example whether you are an adminstritative user or normal user. 

Also you need to know the information about the Linux system you are using.

## Current working directory

Know the current working directory with the command `pwd`{{execute}}

## Linux System Information

Find the system information including hostname, kernel, OS release, version, processor, hardware architecture, hostname and OS name.

Know these details about the system with the command `uname -a`{{execute}}

If you want to know any of the these details individually

Run `uname -s`{{execute}} to know the OS name.

Run `uname -r`{{execute}} to know the release.

Run `uname -v`{{execute}} to know the version.

Run `uname -m`{{execute}} to know machine hardware name.

Run `uname -p`{{execute}} to know processor type.

Run `uname -i`{{execute}} to know hardware platform.

Run `uname -o`{{execute}} to know operating system.

Run `uname -n`{{execute}} to know the hostname.

You have learned how to find system information using **uname** command. 

To know the os release you can also run the command `cat /etc/os-release`{{execute}}

## Your User and Group ID Details

Know the user id, group id with the command `id`{{execute}}

These commands will give you enough info about where you are (current directory), what OS you are using and who(id) you are in the system. This determines the actions you can perform in the system.

## Know Your User Environment Details

Now that you have got the information about the OS environment. It's time for you to know the user environment details. 

A user environment details include the SHELL, HOME DIRECTORY, PATH, HOSTNAME and much more.

Know the details of your user environment variables with the command `env`{{execute}} 

It would display all your environment details, at this stage get the essential information needed for you as beginner.

Run `echo $SHELL`{{execute}} to know the shell that has been assigned to you.

Run `echo $HOME`{{execute}} to know your home directory.

Run `echo $HOSTNAME`{{execute}} to know your linux host name or node name.

Run `echo $PATH`{{execute}} to know path that has been set for you. This determines what commands have been included in your path, so you could directly run commands like pwd. If the command or utilities path are not set you have use the full path of the command.

Actual path of pwd command is /bin/pwd, you can find that by running the command `which pwd`{{execute}}

For example, if /bin is not included in your path you may not able to run even basic commands like pwd. The actual path of pwd command is `/bin/pwd`{{execute}}. In Linux everything is treated as file including the commands (like pwd, ps, ls and so on). 



**Note:** If PATH is not set properly you might get command not found error even though those utilities or commands are installed in your system. So it's important to know the PATH that has been assigned.
