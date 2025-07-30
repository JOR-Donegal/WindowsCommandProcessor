# Moving around directories

We will now examine how to move files around using these commands. Before starting, make sure you are in the **\CLI** directory!

Examine these commands

**copy rubbish.txt rubbish1.txt**

**copy rubbish.txt Backup**

What was the difference in how the command was interpreted?

We can delete files in a directory which is not our working directory, using relative paths, for example

**del Backup/rubbish1.txt**

Now change your working directory to **X:\CLI\Backup** and run the commands

**copy ../rubbish.txt .**\
**dir**

What happened and why?

In many cases, (.) and (..) are very handy, however they do require you to know what your working directory is. One longer but safer option is to use absolute path names. Try using absolute pathnames to copy the file **rubbish.txt** to a backup directory
