## grep

Grep is a command that searches files for certain words or phrases.

For example, to search the word "hello" in "test.txt":

    grep "hello" test.txt
    
You can also search for multiple files, or use the wild card, the asterisk `*`, to search all files in a directory.

    grep "hello" test1.txt test2.txt test3.txt
    
or

    grep "hello" *
    
Just like with cat, there are several different options you can apply to grep to make it more or less specific.

### -i
This option ignores cases in the word or phrase being searched. This means if the word was "key" it would search "KEY" and "keY" and any other case combination in the files specified.

    grep -i "key" *
    
### -l
This option lists only the file name that contains the word or phrase being searched.

    grep -l "hello" *
    
### -r
Similar to cat, this option recursively searches the word or phrase in all sub-directories.
    
    grep -r "hello" *

    