Linux
=====

ColorWall
---------

.. image:: /_static/images/colorwall.png

Install ColorWall dependencies
++++++++++++++++++++++++++++++

If you are running Ubuntu or Debian, at a Terminal prompt run::

    sudo apt-get install python-tk

You will be prompted for your administrative password.

This will install the python-tk package, which is used by the ColorWall project.

Download the ColorWall project
++++++++++++++++++++++++++++++

You'll be writing graphical effects for an existing ColorWall project. Download this ColorWall code and example effects so you're ready to start working with them tomorrow:

Right click the following file, click "Save Target as..." or "Save link as...", and save it to your Desktop directory: :download:`ColorWall.tar.gz </_static/dependancies/ColorWall.tar.gz>`

Find ColorWall.tar.gz on your Desktop and double-click on it. A window will pop up with some options about how to "extract" the file. Leave the defaults where they are and click the "extract" button. That will create a folder on the Desktop called ColorWall containing several files.

Test the ColorWall code
+++++++++++++++++++++++

Start a command prompt and navigate to the Desktop/ColorWall directory where the ColorWall code lives. For example, if the ColorWall project is at /home/jesstess/Desktop/ColorWall::

    cd /home/jesstess/Desktop/ColorWall

will change you into that directory, and::

    ls

will show you the source code files in that directory. One of the files is "run.py", which has a ".py" extension indicating that it is a Python script. Type::

    python run.py

at the command prompt to execute the run.py Python script. You should see a window pop up and start cycling through colorful effects. If you don't, let a staff member know.

Now type::

    python run.py -a -s

at the command prompt to execute the run.py Python script so that it runs only the advanced effects. You should see a window pop up and start cycling through different colorful effects. If you don't, let a staff member know.

You can also run both sets of effects by typing::

    python run.py -a

Success!
++++++++

You've completed setup for the ColorWall project.

Wordplay
--------

.. image:: /_static/images/wordplay.png

Download the Wordplay project
+++++++++++++++++++++++++++++

We've written some skeleton code for the Wordplay project already. Download this code so you're ready to start working with it tomorrow:

Right click the following file, click "Save Target as..." or "Save link as...", and save it to your Desktop directory: :download:`Wordplay.tar.gz </_static/dependancies/Wordplay.tar.gz>`

Find Wordplay.tar.gz on your Desktop and double-click on it to "extract" it. That will create a folder called Wordplay containing several files.

Test the Wordplay code
++++++++++++++++++++++

Start a command prompt and navigate to the Desktop/Wordplay directory where the Wordplay code lives. For example, if the Wordplay project is at /home/jesstess/Desktop/Wordplay::

    cd /home/jesstess/Desktop/Wordplay

will change you into that directory, and::

    ls

will show you the source code files in that directory. One of the files is "words1.py", which has a ".py" extension indicating that it is a Python script. Type::

    python words1.py

at the command prompt to execute the words1.py Python script. You should see a column of English words printed to the screen. If you don't, let a staff member know.

Success!
++++++++

You've completed setup for the Wordplay project.

Twitter
-------

.. image:: /_static/images/twitter.png

Download and extract the Twitter project dependencies
+++++++++++++++++++++++++++++++++++++++++++++++++++++

Click and save these four dependencies to your Desktop:

* :download:`httplib2-0.6.0.zip </_static/dependancies/twitter/httplib2-0.6.0.zip>`
* :download:`simplejson-2.1.6.zip </_static/dependancies/twitter/simplejson-2.1.6.zip>`
* :download:`python-twitter.zip </_static/dependancies/twitter/python-twitter.zip>`
* :download:`python-oauth2.zip </_static/dependancies/twitter/python-oauth2.zip>`

The ".zip" extension on the above files indicates that they are compressed Zip archives. We need to "extract" their contents. To do this, double-click on each file. This will create a directory for each file, containing the source code for the dependency.

Install the Twitter project dependencies
++++++++++++++++++++++++++++++++++++++++

Each of these 4 dependencies has an installer script that we'll need to run at a command prompt to install the software. It is important that the dependencies are installed in the order listed above. For each project, start a command prompt and navigate to the Desktop directory where the source code lives. For example, if the httplib2-0.6.0 project was extracted to /home/jesstess/Desktop/httplib2-0.6.0::

    cd /home/jesstess/Desktop/httplib2-0.6.0

will change you into that directory, and::

    ls

will show you the source code files in that directory. One of the files is "setup.py", which has a ".py" extension indicating that it is a Python script. Type::

    sudo python setup.py install

type in your password, and hit enter to install httplib2.

Navigate to the 3 other dependency directories and run::

    sudo python setup.py install

in all of them to install those dependencies as well.
If you get an error like::

    ImportError: No module named setuptools

you need an extra package. Type::

    sudo apt-get install python-setuptools

Download the Twitter project
++++++++++++++++++++++++++++

We've written some skeleton code for the Twitter project already. Download this code so you're ready to start working with it tomorrow:

* Right click the following file, click "Save Target as..." or "Save link as...", and save it to your Desktop directory: :download:`Twitter.tar.gz </_static/dependancies/twitter/Twitter.tar.gz>`
* Find Twitter.tar.gz on your Desktop and double-click on it to "extract" it. That will create a folder called Twitter containing several files.

Test the Twitter code
+++++++++++++++++++++

Start a command prompt and navigate to the Desktop/Twitter directory where the Twitter code lives. For example, if the Twitter project is at /home/jesstess/Desktop/Twitter::

    cd /home/jesstess/Desktop/Twitter

will change you into that directory, and::

    ls

will show you the source code files in that directory. One of the files is "twitter_api.py", which has a ".py" extension indicating that it is a Python script. Type::

    python twitter_api.py --search=python

at the command prompt to execute the twitter_api.py Python script. You should see the text from 20 tweets containing the word "Python" printed to the screen. If you don't, let a staff member know.

Success!
++++++++

You've completed setup for the Twitter project.

State Capitals
--------------

We'll look at an example Python script that quizzes you on state capitals during the lecture on Saturday.

Right click the following file, click "Save Target as..." or "Save link as...", and save it to your Desktop directory: :download:`state_capitals.py </_static/dependancies/state_capitals.py>`

Success!
--------

You are done installing dependencies for the Saturday projects.
