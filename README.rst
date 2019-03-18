####################
IS 210 Assignment 08
####################
************
Warmup Tasks
************

:College: CUNY School of Professional Studies
:Course-Name: Software Application Programming I
:Course-Code: IS 210

Overview
========

In this assignment, we'll look at some basic uses of conditionals to enforce
control-flow of some simple programs.

Instructions
============

The following tasks will either have you interacting with existing files in
the assignment repository or creating new ones on the fly. Don't forget to add
your interpreter directive, utf-8 encoding, and a short docstring with any new
files that you create!

.. important::

    In these exercises, you may, on occasion, come across a task that requres
    you to research or use a function or method not directly covered by the
    course text. Since Python is such a large language it would be impossible
    for the author to have included descriptions of each and every available
    function which would largely duplicate the offical Python documentation.

    A *vital* skill to successful programming is being comfortable searching
    for and using official language documentation sources like the
    `Python String Documentation`_ page. Throughout our coursework we will be
    practicing both the use of the language in practice and the search skills
    necessary to become functional programmers.

Warmup Tasks
============

Task 01
-------

Use ``raw_input`` to collect user input on the command line.

Specifications
^^^^^^^^^^^^^^

1.  Open a new Jupyter notebook

2.  Use ``raw_input()`` to ask the user a question (any question!) and save
    the result to a variable named ``MY_ANSWER``

Expected Output
^^^^^^^^

.. code:: pycon

    What is your name? Arthur
    >>> print MY_ANSWER
    Arthur

.. note::

    Examples given here are just examples. They are *not* guaranteed to be the
    exact values encountered in your code.

Task 02
-------

Extend our ``raw_input()`` usage and convert the data type of collected user
input.

Specifications
^^^^^^^^^^^^^^

1.  Keep using the same notebook

2.  One a new line, use ``raw_input()`` and a type conversion function
    to ask the user a question and store the result *as an integer* into a
    new variable named ``MY_INTEGER``

Expected Output
^^^^^^^^

.. code:: pycon

    What is the answer to the life the universe and everything? 42
    >>> print MY_INTEGER
    42
    >>> type(MY_INTEGER)
    <type 'int'>


Task 03
-------

Imagine that you were taking an incredibly difficult programming course. The
stress of the course is starting to get to you so your doctor tells you to
start regularly checking your systolic blood pressure. Unfortunately, the
numbers are fairly hard to remember, you'd much rather know your pressure in
common language terms.

Create a simple branching statement to achieve this objective.

Specifications
^^^^^^^^^^^^^^

1.  Work on a new line on your existing notebook

2.  Using a combination of ``raw_input()``, ``if``, ``elif``, and ``else``,
    write a program that asks the user their blood pressure. Compare the blood
    pressure against the following chart and save the Status to a variable
    named ``BP_STATUS``. At the end of the program, print a nice sentence with
    a formatting string to tell you your status and use ``.format()`` to
    replace the formatting string with your ``BP_STATUS``.
    
    .. table:: Blood Pressure Readings
        
        ====== ===== ================
        Start  End   Status
        ====== ===== ================
        --     89    Low
        90     119   Ideal
        120    139   Warning
        140    159   High
        160    --    Emergency
        ====== ===== ================

.. hint::

    Don't forget that the input of ``raw_input`` is a string!

Expected Output
^^^^^^^^

.. code:: console

    $ python -i task_05.py
    What is your blood pressure? 120
    Your status is currently: Warning!

Submission
==========

Code should be submitted via Blackboard as a Jupyter notebook file.

.. _GitHub: https://github.com/
.. _Python String Documentation: https://docs.python.org/2/library/stdtypes.html
