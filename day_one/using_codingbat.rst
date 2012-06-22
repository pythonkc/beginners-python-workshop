Using Codingbat.com
===================

CodingBat is a little different from using Python at the command line or in a text editor like we've been doing. When you use CodingBat, you type your code into a web page and click 'Go' when you want that code to run. You'll still need to make sure you indent all your code to the same level.

For each CodingBat question, you will write a function. CodingBat will run your function with a few different inputs, and will compare the output of the function you wrote to what it knows is the correct answer. If all the outputs are correct for all the inputs, you've written the function correctly!

We like CodingBat because it gives you immediate feedback on how close your function is to being correct.

Let's walk through an example, the sumTwoNumbers exercise.
If you visit that exercise web page, this is what you'll see:

.. image:: /_static/images/cbat_openingscreen.png

This screen:

* describes the problem (write a function to add any two numbers together)
* shows you some of the inputs that CodingBat will use to test the function you've written, and the outputs that CodingBat expects to see returned from your function for each input.
* The inputs are the values in the parentheses, and the expected output is the value pointed to by the arrows:

.. image:: /_static/images/cbat_io.png

If you simply click "Go" without typing anything in the box, CodingBat gives you an error on the right hand side of the screen:

.. image:: /_static/images/cbat_nocode.png

Let's add some code. The function signature (the def sumTwoNumbers(first, second): part) has already been written for you. You'll write the rest of the function -- remember to indent everything inside the function, and remember to return your result instead of printing it!

.. image:: /_static/images/cbat_wrong.png

Hmm. I've got one correct and two wrong. Oh! I see - I typed in first twice, when instead I should have used second:

.. image:: /_static/images/cbat_correct.png

Great! All the tests are green, so we know that we've done this problem correctly and can move on to the next one.

What CodingBat is doing is the same as when you write a function in your text editor or at the Python prompt and then run it a few times, like this::

    >>> def sumTwoNumbers(first, second):
    ...    return first + second
    ... 
    >>> sumTwoNumbers(2,3)
    5
    >>> sumTwoNumbers(5,5)
    10
    >>> sumTwoNumbers(10,-10)
    0

Perfect!

Now that you are a CodingBat master, let's get started.

http://codingbat.com/home/bostonpythonworkshop@gmail.com/Friday