In Linux operating system you should know the directory where you are and as what user you have logged in to the system.

These two determines what level of access you have been provided, for example whether you are an adminstritative user or normal user. 

Administrative privileges are given through a command called as **sudo -l** or in the **/etc/sudoers** confifguration file.

## Current working directory

Know the current working directory with the command `pwd`{{execute}}

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





