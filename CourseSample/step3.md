Create directories and subdirectories using the `mkdir` command and switch to the respective directories using `cd` command.

## Creating a Directory

Know how to find your home directory with the command `echo $HOME` or `cd ~ && pwd`

Know how to create a directory with the command `mkdir dir1`, dir1 is the name of the directory.

Know how to create mulitple directories with the command `mkdir dir2 dir3 dir4`

Know how to create a directory along with sub-directory using command `mkdir -p dir5/subdir5`, the `-p` options specifies that it should create sub-directory as part of the directory. 


Know how to switch or change directory to dir1, with the command `cd dir1`. 

Now that you have switched to dir1, switch back to your home directory with the command `cd ~` or `cd` or `cd $HOME`. These two commands will take you to your home directory irrespective of the directory you are operating currently. 


## Changing Directory Using Absolute Path

Before changing directory, know your current working directory with command `pwd`.

Know how to change to /tmp directory, execute `cd /tmp` 

To switch or change to /opt directory, execute `cd /opt`. This method of using full path starting with / is called absolute path method.


## Changing Directory Using Relative Path

Know how to switch to home directory with `cd ~`{{execute}} to return to the home directory. Here we are using symbols instead of full path of home directory and is called as relative path. 

You can return to previous directory with the command `cd -`, confirm it with the command `pwd`.

Switch back to dir1 with the command `cd $HOME/dir1` and then type `pwd` to know your current working directory. 

Using relative path switch to dir2 with the command `cd ../dir2`, confirm with `pwd`{{execute}} command.

**.** represents current directory

**..** represents one level above current directory, in this case while switching from $HOME/dir1 to $HOME/dir2 the **..** represents `cd $HOME && pwd`.