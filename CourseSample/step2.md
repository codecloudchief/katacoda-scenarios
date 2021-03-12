Now that you have got the information about the OS and user environment. It's time for you to know how to create files and directories. 

File is where data is stored and directories are just a pointer and container of files.

## File Creation

A file can be created in multiple ways, in this lab you will learn how to create it using `touch`, `cat` and `vi`(High level, refer detailed VI Editor course for additional in depth understanding of it)

Know how to create an empty file with `touch file1`.

Know how to create a file using `cat > file2`, the `>` symbol after `cat` command denotes to create a file.

Type the contents of the file like `This is file2 contents`{{execute}}, then press `ctrl + d` to save and exit the file.

View the contents of the file you created using `cat file2` command.

Now let's append the **file2** with additional content, with the command `cat >> file2`. The `>>` symbol after `cat` command denotes to append a file with new content at the end of the file.

`vi` is command based editor and `nano` is simple text editor and are the other ways to create/edit files. 

Know how to create multiple zero byte file with `touch file3 file4 file5`. 

Run `ls`{{execute}} to list the files in your current working directory `pwd`{{execute}}

Run `ls -l`{{execute}} to long list the files in your current working directory `pwd`{{execute}}


Next step is to create a directories in Linux OS. 