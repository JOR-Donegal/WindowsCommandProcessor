# Paths

You will recall that

(.) means the current directory, so typing **cd .** means stay where you are.

(..) means the parent of the current directory, so typing **cd ..** will take you one directory up the hierarchy.

We have used the term **working directory** previously to describe the current working directory the shell is operating in.

In DOS if we type **cd** on its own, it will return the current path.

Before we type a command, we really need to know what our current directory is. We have several types of paths and I will briefly explain them now.&#x20;

An **absolute path** is the path to a file with respect to the root. In Windows if I want to delete a file deep in my directory structure, I can type **del C:\users\\**_**username**_**\CLI\Backup\rubbish.txt** and regardless of which working directory I am in, this will work.

I can also delete a file using a **relative path** to my working directory. Suppose I have a working directory of **C:\users\\**_**username**_**\CLI** and I want to delete the same file as above.&#x20;

I could type **del .\Backup\rubbish.txt** and this would still work.
