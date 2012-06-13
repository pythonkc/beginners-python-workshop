Windows
=======

Terminal Navigation
-------------------

The filesystem on your computer is like a tree made up of folders (also called "directories") and files. The filesystem has a root directory called /, and everything on your computer lives in subdirectories of this root directory.

We often navigate the filesystem graphically by clicking on graphical folders. We can do the exact same navigation from the command line.

There are two commands that we'll be using at a command prompt to navigate the filesystem on your computer:

* dir
* cd

`dir` lists the contents of a directory.

`cd` moves you into a new directory (it stands for "change directory").

Let's practice using these commands.

Open a command prompt:
----------------------

* On Windows Vista or Windows 7: click on the Start menu (the Windows logo in the lower left of the screen), type cmd into the Search field directly above the Start menu button, and click on "cmd" in the search results above the Search field.
* On Windows XP: click on the Start menu (the Windows logo in the lower left of the screen), click on "Run...", type cmd into the text box, and hit enter.

Practice using dir and cd
-------------------------

Type each of these commands and hit enter::

    dir

This lists all the files in your home directory::

    cd C:\

This will change you into the C:\\ directory::

    dir

This lists the contents of the C:\\ directory::

    cd Users

This will change you into the Users subdirectory of the C:\\ directory::

    dir

You should see the names of all the files and directories in C:\\Users::

    cd ..

`..` means "parent directory", so this command moved you up to the parent directory. You were in C:\\Users, so now you are in C:\\, the root directory::

    dir

This lists the contents of the root directory, confirming where you are.

Tips
----

* You can use Tab to auto-complete directory and file names. So from inside the root directory, if you type cd Use and hit Tab, the command prompt will auto-complete the directory name, and you can then hit enter to change into the C:\\Users directory.
* The command prompt maintains a command history. You can use the up arrow to cycle through old commands.
* Note that the text that makes up the command prompt changes as you move around directories. The command prompt will always give the full directory path to your current directory.

Check your understanding
------------------------

Answer these questions. Experiment at the command line if you need to! If you aren't sure about an answer, ask a helper.

* What directory are you in after starting a new command line prompt?
* After starting a new command line prompt, how would you get to the root directory?
* How do you check what files and directories are in your current working directory?
* If you are in directory C:\\Users, and you want to get to C:\\Users\\jesstess\\projects, how would you do that?
* What are 2 ways to avoid typing out a full navigation command? (hint: one requires that you've run the command before)
* What is the difference between a command prompt and a Python prompt?

Success!
--------

You've practiced using `dir` and `cd` to navigate your computer's filesystem from the command prompt.