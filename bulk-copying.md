# Bulk Copying

Some of the most common commands we use are those that allow us to copy. In DOS/Windows, try running the commands

**help copy**

**help xcopy**

**help robocopy**

We know how to use **copy&#x20;**_**source destination**_ and the other commands are just a sophisticated version allowing recursive copies of files and directories to be copied.

Go to your home directory and try the command **xcopy .\CLI .\CLI2**

Use the tree command to verify what happened.

Empty directories were ignored and there were no files in any of the backup directories.

We could use some of the switches in **xcopy** to make life easier. Try the command&#x20;

**xcopy .\CLI .\CLI3 /E** /I /F&#x20;

and use the command **tree** to ensure it worked.

There is a more modern command called **robocopy** which is much more appropriate for use over a network on a modern system. Using help, figure out how to create a directory **CLI4** with all the subdirectories and files within.

Now clean up the mess; delete the directories you have created.
