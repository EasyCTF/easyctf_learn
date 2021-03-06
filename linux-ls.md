# ls
The command `ls` lists directory contents. A directory is a file that consists solely of a set of other files, like a folder.

There are several options you can add to this command such as `-a`, `-r`, `-R`, `-X`, and many more.

## -a
This option will list all entries in a directory, even ones starting with `.` .

## -r
This option lists entries in reverse alphabetical order.

## -R
This option recursively lists the contents of all sub-directories inside this one.

## -X
This option lists entries sorted alphabetically by entry extension

## -l
This option gives you a more complete listing of all of the files along with owner and permsisions.

To use:

```bash
ls [option] [directory location]
```

If a directory location is not specified, it will use the current directory you are in.

For example:

```bash
ls -r /usr
```

Would output the files in `/usr` in reverse alphabetical order.