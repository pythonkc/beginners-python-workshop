Windows
=======

Color Wall
----------

.. image:: /_static/images/colorwall.png

Download the ColorWall project
++++++++++++++++++++++++++++++

You'll be writing graphical effects for an existing ColorWall project. Download this ColorWall code and example effects so you're ready to start working with them tomorrow:

* Right click the following file, click "Save Target as..." or "Save link as...", and save it to your Desktop directory: :download:`ColorWall.zip </_static/dependancies/ColorWall.zip>`

* The ".zip" extension on the above file indicates that it is a compressed Zip archive. We need to "extract" its contents. To do this, click on "Start", then "Computer", and navigate to your Desktop directory. Find ColorWall.zip on your Desktop and double-click on it to "unzip" it. That will create a folder called ColorWall containing several files.

Test the ColorWall code
+++++++++++++++++++++++

Start a command prompt and navigate to the Desktop\ColorWall directory where the ColorWall code lives. For example, if the ColorWall project is at C:\Users\jesstess\Desktop\ColorWall::

    cd C:\Users\jesstess\Desktop\ColorWall

will change you into that directory, and::

    dir

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

* Right click the following file, click "Save Target as..." or "Save link as...", and save it to your Desktop directory: :download:`Wordplay.zip </_static/dependancies/Wordplay.zip>`
* Find Wordplay.zip on your Desktop and double-click on it to "unzip" it. That will create a folder called Wordplay containing several files.

Test the Wordplay code
++++++++++++++++++++++

Start a command prompt and navigate to the Desktop\Wordplay directory where the Wordplay code lives. For example, if the Wordplay project is at C:\Users\jesstess\Desktop\Wordplay::

    cd C:\Users\jesstess\Desktop\Wordplay

will change you into that directory, and::

    dir

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

Click and save these four dependencies to your Desktop directory:

* :download:`httplib2-0.6.0.zip </_static/dependancies/twitter/httplib2-0.6.0.zip>`
* :download:`simplejson-2.1.6.zip </_static/dependancies/twitter/simplejson-2.1.6.zip>`
* :download:`python-twitter.zip </_static/dependancies/twitter/python-twitter.zip>`
* :download:`python-oauth2.zip </_static/dependancies/twitter/python-oauth2.zip>`

The ".zip" extension on the above files indicates that they are compressed Zip archives. We need to "extract" their contents. To do this, click on "Start", then "Computer", and navigate to your Desktop directory. For each of the 4 zip files, click on the file and click the "Extract all files" button to extract the contents. This will create a directory for each file, containing the source code for the dependency.

Install the Twitter project dependencies
++++++++++++++++++++++++++++++++++++++++

Each of these 4 dependencies has an installer script that we'll need to run at a command prompt to install the software. **It is important that the dependencies are installed in the order listed above.** For each project, start a command prompt and navigate to the Desktop directory where the source code lives. For example, if the httplib2-0.6.0 project was extracted to C:\Users\jesstess\Desktop\httplib2-0.6.0::

    cd C:\Users\jesstess\Desktop\httplib2-0.6.0

will change you into that directory, and::

    dir

will show you the source code files in that directory. One of the files is "setup.py", which has a ".py" extension indicating that it is a Python script. Type::

    python setup.py install

and hit enter to install httplib2.

Navigate to the 3 other dependency directories (in the order you downloaded them: simplejson-2.1.6, python-twitter, python-oauth2) and run::

    python setup.py install

in all of them to install those dependencies as well.

Download the Twitter project
++++++++++++++++++++++++++++

We've written some skeleton code for the Twitter project already. Download this code so you're ready to start working with it tomorrow:

* Right click the following file, click "Save Target as..." or "Save link as...", and save it to your Desktop directory :download:`Twitter.zip </_static/dependancies/twitter/Twitter.zip>`
* Find Twitter.zip on your Desktop and double-click on it to "unzip" it. That will create a folder called Twitter containing several files.

Test the Twitter code
+++++++++++++++++++++

Start a command prompt and navigate to the Desktop\Twitter directory where the Twitter code lives. For example, if the Twitter project is at C:\Users\jesstess\Desktop\Twitter::

    cd C:\Users\jesstess\Desktop\Twitter

will change you into that directory, and::

    dir

will show you the source code files in that directory. One of the files is "twitter_api.py", which has a ".py" extension indicating that it is a Python script. Type::

    python twitter_api.py --search=python

at the command prompt to execute the twitter_api.py Python script. You should the text from 20 tweets containing the word "Python" printed to the screen. If you don't, let a staff member know.

Success!
++++++++

You've completed setup for the Twitter project

State Capitals
--------------

We'll look at an example Python script that quizzes you on state capitals during the lecture on Saturday.

Right click the following file, click "Save Target as..." or "Save link as...", and save it to your Desktop directory :download:`state_capitals.py </_static/dependancies/state_capitals.py>`

Success!
--------

You are done installing dependencies for the Saturday projects.

