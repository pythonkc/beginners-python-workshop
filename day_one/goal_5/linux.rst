Linux
=====

Start your text editor
----------------------

* Launch the GEdit text editor. See the Linux text editor setup instructions for the steps to do this.
* Start a new, blank text file.

Write and save a short Python script
------------------------------------

* Add the following line to your new text file::

    print "Hello World!"

* Save the script as hello.py in your home directory. The .py extension indicates that this file contains Python code.

Run the script
--------------

* Start a command prompt. See the terminal navigation on Linux instructions for the steps to do this. Recall that a terminal prompt will look like jesstess$ and a Python prompt will look like >>>. Make sure you are at a terminal prompt and not a Python prompt; if you are at a Python prompt, you can type exit() on a line by itself and then hit enter to exit Python and return to a terminal prompt.
* Navigate to your home directory from a command prompt, using the ls, pwd, and cd commands. See the terminal navigation on Linux instructions for a refresher on using these commands. Don't hesitate to get help from a staff member on this step if you need it -- it's a new way of navigating your computer, so it may be unintuitive at first!
* Once you are in your home directory, you'll see hello.py in the output of ls.
* Type::

    python hello.py

and hit enter. Doing this will cause Python to execute the contents of that script -- it should print "Hello World!" to the screen. What you've done here is run the Python application with an argument -- the name of a file, in this case "hello.py". Python knows that when you give it a file name as an argument, it should execute the contents of the provided file. You get the same result as if you typed::

    print "Hello World!"

at a Python prompt and hit enter.

Success!
--------

You created and ran your first Python script!

* When you run the python command by itself, you start a Python prompt. You can execute Python code interactively at that prompt.
* When you run the python command with a file name as an argument, Python executes the Python code in that file.