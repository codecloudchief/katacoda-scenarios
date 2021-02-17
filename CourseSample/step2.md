Now that you have got the information about the OS environment. It's time for you to know the user environment details. 

A user environment details include the SHELL, HOME DIRECTORY, PATH, HOSTNAME and much more.

Know the details of your user environment variables with the command `env`{{execute}} 

It would all user environment details, at this stage get the essential information needed for you as beginner.

Run `echo $SHELL`{{execute}} to know the shell that has been assigned to you.

Run `echo $HOME`{{execute}} to know your home directory.

Run `echo $HOSTNAME`{{execute}} to know your linux host name or node name.

Run `echo $PATH`{{execute}} to know path that has been set for you. This determines what commands have been included in your path, so you could directly run commands like pwd. If the command or utilities path are not set you have use the full path of the command.

Actual path of pwd command is /bin/pwd, you can find that by running the command `which pwd`{{execute}}

For example, if /bin is not included in your path you may not able to run even basic commands like pwd. The actual path of pwd command is /bin/pwd. In Linux everything is treated as file including the commands (or binaries). 



**Note:** If PATH is not set properly you might get command not found error even they those utilities or commands are installed in your system. So it's important to know the PATH that has been assigned.