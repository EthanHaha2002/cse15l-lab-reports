# Lab Report 1

## ls:
---
Example screenshot for ls:
---
![Image](ls_example.jpg)

no argument
---
For "ls", the working directory was /home and it output the available directory: "Lecture1". No output error.

with directory argument
---
For "ls lecture1", the working directory is still /home and the output is all the files within "lecture1". No output error.

with path to file argument
---
The working directory is still /home and the output is just the path from the home directory up to the point of the file. No output error.

Code block
---
![Image](ls_codeblock.jpg)

Output
---
![Image](ls_output.jpg)

***cd:***

Example screenshot for cd:
---
![Image](cd_example.jpg)

no argument
---
The working directory is /home. There is no output as it moves to a new command line but using cd without an argument anywhere other than the home directory will return you back to the home directory. No output error.

with directory argument
---
The working directory is now "/home/lecture1" and there is not output besides the indicator that you are now working in a new directory. No output error.

with path to file argument
---
The working directory is still going to be "/home/lecture1". There is an output error indicating that the command is not possible as you're attempting to change directories into a file which is not a directory.

Code block
---
![Image](cd_codeblock.jpg)

Output
---
![Image](cd_output.jpg)

Example screenshot for cat:
---
![Image](cat_example2.jpg)

no argument
---
The working directory would be "/home". There wouldn't be an output at first-- it'd be empty but as soon as you type a word it will print out the same word right after.

with directory argument
---
The working directory would actually be "/home" here. The message "lecture1 is a directory" would print as there is nothing to concatenate.

with path to file argument
---
The working directory would be "/home/lecture1/messages". The output was "ls" for me.

Code block
---
![Image](cat_codeblock.jpg)

Output
---
![Image](cat_output.jpg)
