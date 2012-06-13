Linux
=====

Terminal Navigation
-------------------

The filesystem on your computer is like a tree made up of folders (also called "directories") and files. The filesystem has a root directory called /, and everything on your computer lives in subdirectories of this root directory.

We often navigate the filesystem graphically by clicking on graphical folders. We can do the exact same navigation from the command line.

There are three commands that we'll be using at a command prompt to navigate the filesystem on your computer:

* ``ls``
* ``pwd``
* ``cd``

``ls`` lists the contents of a directory.

``pwd`` gives the full directory path to your current directory.

``cd`` moves you into a new directory (it stands for "change directory").

Let's practice using these commands.

Open a command prompt
---------------------

You can find the Terminal application at Applications/Accessories/Terminal, or it may already be on your menu bar.

Practice using ``ls``, ``pwd``, and ``cd``
------------------------------------------

(that's an l the letter, not the number 1)

Type each of these commands and hit enter::

    ls

This lists all the files in your home directory::

    pwd

This displays the full directory path to your current directory, which is your home directory::

    cd /

This will change you into the / root directory::

    ls

This lists the contents of the / root directory::

    cd home

This will change you into the home subdirectory of the / root directory::

    ls

You should see a list of all the files in /home, including the directory for your username -- your home directory::

    pwd

This displays the full directory path to your current directory, /home::

    cd ..

``..`` means "parent directory", so this command moved you up to the parent directory. You were in /home, so now you are in /, the root directory::

    ls

This lists the contents of the root directory, confirming where you are.

Tips
----

* You can use Tab to auto-complete directory and file names. So from inside the root directory /, if you type cd ho and hit Tab, the command prompt will auto-complete the directory name, and you can then hit enter to change into the /home directory.
* The command prompt maintains a command history. You can use the up arrow to cycle through old commands.

Check your understanding
------------------------

Answer these questions. Experiment at the command line if you need to! If you aren't sure about an answer, ask a helper.

* What directory are you in after starting a new command line prompt?
* After starting a new command line prompt, how would you get to the root directory?
* How do you check what files and directories are in your current working directory?
* If you are in directory /home, and you want to get to /home/jesstess/projects, how would you do that?
* What are 2 ways to avoid typing out a full navigation command? (hint: one requires that you've run the command before)
* What is the difference between a command prompt and a Python prompt?

Success!
--------

You've practiced using ``ls``, ``pwd``, and ``cd`` to navigate your computer's filesystem from the command prompt.