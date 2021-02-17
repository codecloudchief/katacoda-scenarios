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

## Your ID Details

Know the user id, group id with the command `id`{{execute}}

This will give you enough system about where you are (current directory), what OS you are using and who(id) you are in the system. This determines the actions you can perform in the system.



