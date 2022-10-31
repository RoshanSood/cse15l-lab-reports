## Part 1 - Commands
- The "find" command
* This command lists all files in current folder and subfolders with given pattern
![Image](files.png)
* Ex. "find some-files -name *.txt/" would find all the files in the directory which are:
![Image](filesoutput.png)


### Find Alternatives
* An alternative to the find command is the "-type" command
* -type is tool similar to the find command that is used to find files on a system
* The command is

``` 
# find -type command 1

find -type technical *.txt

Output: 

```

``` 
# find -type command 2

find technical/911 -type *.txt

Output: 

```

``` 
# find -type command 3

find -type technical/biomed -type *.txt 

Output: 

```


* The type command is designed to find entries in a filesystem by their name or extension. It is useful because it is another way to easily access specific files in a system without explicity searching their names or using the "find" command to find them. This makes finding files easy by just specifying the type to find them.
* Type is a efficient command as it matches the extension to the file

### -name alternative
* -name searches for the file by the extension or name
* The command is

``` 
# find name command

find technical -name *.txt 

Output: 

```

``` 
# find name command 2

find technical -name "government" 

Output: 

```

``` 
# find name command 3

find technical -name "chapter" 

Output: 

```



* The name command is designed to find entries based off of arguments passed in like extension or file name. This is useful because it can access a specific file by searching through the file type, adding a new way to access a file. 
* Find name can be used to find files with a certain name or extension



### locate alternative 



