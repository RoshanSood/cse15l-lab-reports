## Part 1 - Vim Commands
* The shortest sequence of vim commands for the task:
```
Changing the name of the start parameter and its uses to base
```
* First of all, to vim into the file we type vim DocSearchServer.java into the terminal

* vim allows you to edit text in files through the terminal

Before we change anything the code looks like this:
![Image](original.png)
* Next, to change name to 'base' we use the command

```
:
%
s
/
start
 <Enter>
base
<Enter>
```
* The overall purpose of these commands is to find all instances of start in our file and change it to base

* Specifically, the combination of commands, the : and s allows us to highlight the lines we want to change, which are the lines that only contains start. On the other hand, the % command reads the whole file for 'start' because it is what we aim to replace in our file 

* Next, in order to actually replace start with base, we need to use the / command. This command allows us to type in a string that we want to replace with another string. 

* After we type in start, we need to press enter and then type in base and enter again to switch all instances of name with base. This command first takes in what needs to be replaced, then an enter to move to the next part of the command, then the string we want to replace with, and lastly another enter to complete the replace of strings.

* Overall, this command allows us to switch all instances the word start to base in our file.

It should look like this: 
![Image](after.png)

### Part 2
* It took me roughly a minute for the first task mainly because I had to login to the server and scp which took the majority of the time
* The second step took me roughly 30 seconds since I was already logged into the server and only had to run a few commands to edit and run the file 

### Questions
"Which of these two styles would you prefer using if you had to work on a program that you were running remotely, and why?"

* I would prefer the second step mainly because it takes less time. Moreover, making the edit it vim is easier because I can use commands like ':%s/' to find and replace effiently. Lastly, vim makes it easy to edit and run files in a server without constantly scp'ing to them.

"What about the project or task might factor into your decision one way or another? (If nothing would affect your decision, say so and why!)"

* The use of a server would factor my decision because it is just so much easier to use vim and edit files from the server than using the first style. Moreover, this style would save time and make editing/running code more efficent. This is significant because the use vim is mainly utilized for server work since it fosters efficiency as you can edit and run without constant copying and logging into the server from your local machine.

