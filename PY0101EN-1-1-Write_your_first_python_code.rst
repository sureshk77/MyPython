.. raw:: html

   <center>

.. raw:: html

   </center>

Writing Your First Python Code
==============================

Estimated time needed: **25** minutes

Objectives
----------

After completing this lab you will be able to:

-  Write basic code in Python
-  Work with various types of data in Python
-  Convert the data from one type to another
-  Use expressions and variables to perform operations

.. raw:: html

   <h2>

Table of Contents

.. raw:: html

   </h2>

.. container:: alert alert-block alert-info

   ::

      <ul>
          <li>
              <a href="https://#hello">Say "Hello" to the world in Python</a>
              <ul>
                  <li><a href="https://version/?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDeveloperSkillsNetworkPY0101ENSkillsNetwork19487395-2021-01-01">What version of Python are we using?</a></li>
                  <li><a href="https://comments/?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDeveloperSkillsNetworkPY0101ENSkillsNetwork19487395-2021-01-01">Writing comments in Python</a></li>
                  <li><a href="https://errors/?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDeveloperSkillsNetworkPY0101ENSkillsNetwork19487395-2021-01-01">Errors in Python</a></li>
                  <li><a href="https://python_error/?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDeveloperSkillsNetworkPY0101ENSkillsNetwork19487395-2021-01-01">Does Python know about your error before it runs your code?</a></li>
                  <li><a href="https://exercise/?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDeveloperSkillsNetworkPY0101ENSkillsNetwork19487395-2021-01-01">Exercise: Your First Program</a></li>
              </ul>
          </li>
          <li>
              <a href="https://#types_objects">Types of objects in Python</a>
              <ul>
                  <li><a href="https://int/?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDeveloperSkillsNetworkPY0101ENSkillsNetwork19487395-2021-01-01">Integers</a></li>
                  <li><a href="https://float/?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDeveloperSkillsNetworkPY0101ENSkillsNetwork19487395-2021-01-01">Floats</a></li>
                  <li><a href="https://convert/?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDeveloperSkillsNetworkPY0101ENSkillsNetwork19487395-2021-01-01">Converting from one object type to a different object type</a></li>
                  <li><a href="https://bool/?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDeveloperSkillsNetworkPY0101ENSkillsNetwork19487395-2021-01-01">Boolean data type</a></li>
                  <li><a href="https://exer_type/?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDeveloperSkillsNetworkPY0101ENSkillsNetwork19487395-2021-01-01">Exercise: Types</a></li>
              </ul>
          </li>
          <li>
              <a href="https://#https://exp/?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDeveloperSkillsNetworkPY0101ENSkillsNetwork19487395-2021-01-01ressions">Expressions and Variables</a>
              <ul>
                  <li><a href="exp">Expressions</a></li>
                  <li><a href="https://exer_exp/?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDeveloperSkillsNetworkPY0101ENSkillsNetwork19487395-2021-01-01">Exercise: Expressions</a></li>
                  <li><a href="https://var/?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDeveloperSkillsNetworkPY0101ENSkillsNetwork19487395-2021-01-01">Variables</a></li>
                  <li><a href="https://exer_exp_var/?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDeveloperSkillsNetworkPY0101ENSkillsNetwork19487395-2021-01-01">Exercise: Expression and Variables in Python</a></li>
              </ul>
          </li>
      </ul>
      <p>
          Estimated time needed: <strong>25 min</strong>
      </p>

.. raw:: html

   <hr>

.. raw:: html

   <h2 id="hello">

Say “Hello” to the world in Python

.. raw:: html

   </h2>

When learning a new programming language, it is customary to start with
an “hello world” example. As simple as it is, this one line of code will
ensure that we know how to print a string in output and how to execute
code within cells in a notebook.

.. raw:: html

   <hr/>

.. container:: alert alert-success alertsuccess

.. raw:: html

   <hr/>

.. code:: ipython3

    # Try your first Python output
    
    print('Hello, Python!')

After executing the cell above, you should see that Python prints Hello,
Python!. Congratulations on running your first Python code!

.. raw:: html

   <hr/>

.. container:: alert alert-success alertsuccess

   ::

      [Tip:] <code>print()</code> is a function. You passed the string <code>'Hello, Python!'</code> as an argument to instruct Python on what to print.

.. raw:: html

   <hr/>

.. raw:: html

   <h3 id="version">

What version of Python are we using?

.. raw:: html

   </h3>

.. raw:: html

   <p>

There are two popular versions of the Python programming language in use
today: Python 2 and Python 3. The Python community has decided to move
on from Python 2 to Python 3, and many popular libraries have announced
that they will no longer support Python 2.

.. raw:: html

   </p>

.. raw:: html

   <p>

Since Python 3 is the future, in this course we will be using it
exclusively. How do we know that our notebook is executed by a Python 3
runtime? We can look in the top-right hand corner of this notebook and
see “Python 3”.

.. raw:: html

   </p>

.. raw:: html

   <p>

We can also ask Python directly and obtain a detailed answer. Try
executing the following code:

.. raw:: html

   </p>

.. code:: ipython3

    # Check the Python Version
    
    import sys
    print(sys.version)

.. raw:: html

   <hr/>

.. container:: alert alert-success alertsuccess

   ::

      [Tip:] <code>sys</code> is a built-in module that contains many system-specific parameters and functions, including the Python version in use. Before using it, we must explictly <code>import</code> it.

.. raw:: html

   <hr/>

.. raw:: html

   <h3 id="comments">

Writing comments in Python

.. raw:: html

   </h3>

.. raw:: html

   <p>

In addition to writing code, note that it’s always a good idea to add
comments to your code. It will help others understand what you were
trying to accomplish (the reason why you wrote a given snippet of code).
Not only does this help other people understand your code, it can also
serve as a reminder to you when you come back to it weeks or months
later.

.. raw:: html

   </p>

.. raw:: html

   <p>

To write comments in Python, use the number symbol # before writing your
comment. When you run your code, Python will ignore everything past the
# on a given line.

.. raw:: html

   </p>

.. code:: ipython3

    # Practice on writing comments
    
    print('Hello, Python!') # This line prints a string
    # print('Hi')

.. raw:: html

   <p>

After executing the cell above, you should notice that This line prints
a string did not appear in the output, because it was a comment (and
thus ignored by Python).

.. raw:: html

   </p>

.. raw:: html

   <p>

The second line was also not executed because print(‘Hi’) was preceded
by the number sign (#) as well! Since this isn’t an explanatory comment
from the programmer, but an actual line of code, we might say that the
programmer commented out that second line of code.

.. raw:: html

   </p>

.. raw:: html

   <h3 id="errors">

Errors in Python

.. raw:: html

   </h3>

.. raw:: html

   <p>

Everyone makes mistakes. For many types of mistakes, Python will tell
you that you have made a mistake by giving you an error message. It is
important to read error messages carefully to really understand where
you made a mistake and how you may go about correcting it.

.. raw:: html

   </p>

.. raw:: html

   <p>

For example, if you spell print as frint, Python will display an error
message. Give it a try:

.. raw:: html

   </p>

.. code:: ipython3

    # Print string as error message
    
    frint("Hello, Python!")

.. raw:: html

   <p>

The error message tells you:

.. raw:: html

   <ol>

.. raw:: html

   <li>

where the error occurred (more useful in large notebook cells or
scripts), and

.. raw:: html

   </li>

.. raw:: html

   <li>

what kind of error it was (NameError)

.. raw:: html

   </li>

.. raw:: html

   </ol>

.. raw:: html

   <p>

Here, Python attempted to run the function frint, but could not
determine what frint is since it’s not a built-in function and it has
not been previously defined by us either.

.. raw:: html

   </p>

.. raw:: html

   <p>

You’ll notice that if we make a different type of mistake, by forgetting
to close the string, we’ll obtain a different error (i.e., a
SyntaxError). Try it below:

.. raw:: html

   </p>

.. code:: ipython3

    # Try to see built-in error message
    
    print("Hello, Python!)

.. raw:: html

   <h3 id="python_error">

Does Python know about your error before it runs your code?

.. raw:: html

   </h3>

Python is what is called an interpreted language. Compiled languages
examine your entire program at compile time, and are able to warn you
about a whole class of errors prior to execution. In contrast, Python
interprets your script line by line as it executes it. Python will stop
executing the entire program when it encounters an error (unless the
error is expected and handled by the programmer, a more advanced subject
that we’ll cover later on in this course).

Try to run the code in the cell below and see what happens:

.. code:: ipython3

    # Print string and error to see the running order
    
    print("This will be printed")
    frint("This will cause an error")
    print("This will NOT be printed")

.. raw:: html

   <h3 id="exercise">

Exercise: Your First Program

.. raw:: html

   </h3>

.. raw:: html

   <p>

Generations of programmers have started their coding careers by simply
printing “Hello, world!”. You will be following in their footsteps.

.. raw:: html

   </p>

.. raw:: html

   <p>

In the code cell below, use the print() function to print out the
phrase: Hello, world!

.. raw:: html

   </p>

.. code:: ipython3

    # Write your code below. Don't forget to press Shift+Enter to execute the cell
    print ("hello world")


.. parsed-literal::

    hello world


.. raw:: html

   <details>

.. raw:: html

   <summary>

Click here for the solution

.. raw:: html

   </summary>

.. code:: python

   print("Hello, world!")

.. raw:: html

   </details>

.. raw:: html

   <p>

Now, let’s enhance your code with a comment. In the code cell below,
print out the phrase: Hello, world! and comment it with the phrase Print
the traditional hello world all in one line of code.

.. raw:: html

   </p>

.. code:: ipython3

    # Write your code below. Don't forget to press Shift+Enter to execute the cell
    print ("Hello, world!")


.. parsed-literal::

    Hello, world!


.. raw:: html

   <details>

.. raw:: html

   <summary>

Click here for the solution

.. raw:: html

   </summary>

.. code:: python

   print("Hello, world!") # Print the traditional hello world

.. raw:: html

   </details>

.. raw:: html

   <hr>

.. raw:: html

   <h2 id="types_objects" align="center">

Types of objects in Python

.. raw:: html

   </h2>

.. raw:: html

   <p>

Python is an object-oriented language. There are many different types of
objects in Python. Let’s start with the most common object types:
strings, integers and floats. Anytime you write words (text) in Python,
you’re using character strings (strings for short). The most common
numbers, on the other hand, are integers (e.g. -1, 0, 100) and floats,
which represent real numbers (e.g. 3.14, -42.0).

.. raw:: html

   </p>



.. raw:: html

   <p>

The following code cells contain some examples.

.. raw:: html

   </p>

.. code:: ipython3

    # Integer
    
    11

.. code:: ipython3

    # Float
    
    2.14

.. code:: ipython3

    # String
    
    "Hello, Python 101!"

.. raw:: html

   <p>

You can get Python to tell you the type of an expression by using the
built-in type() function. You’ll notice that Python refers to integers
as int, floats as float, and character strings as str.

.. raw:: html

   </p>

.. code:: ipython3

    # Type of 12
    
    type(12)

.. code:: ipython3

    # Type of 2.14
    
    type(2.14)

.. code:: ipython3

    # Type of "Hello, Python 101!"
    
    type("Hello, Python 101!")

.. raw:: html

   <p>

In the code cell below, use the type() function to check the object type
of 12.0.

.. code:: ipython3

    # Write your code below. Don't forget to press Shift+Enter to execute the cell
    type (12.0)





.. parsed-literal::

    float



.. raw:: html

   <details>

.. raw:: html

   <summary>

Click here for the solution

.. raw:: html

   </summary>

.. code:: python

   type(12.0)

.. raw:: html

   </details>

.. raw:: html

   <h3 id="int">

Integers

.. raw:: html

   </h3>

.. raw:: html

   <p>

Here are some examples of integers. Integers can be negative or positive
numbers:

.. raw:: html

   </p>



.. raw:: html

   <p>

We can verify this is the case by using, you guessed it, the type()
function:

.. code:: ipython3

    # Print the type of -1
    
    type(-1)

.. code:: ipython3

    # Print the type of 4
    
    type(4)

.. code:: ipython3

    # Print the type of 0
    
    type(0)

.. raw:: html

   <h3 id="float">

Floats

.. raw:: html

   </h3>

.. raw:: html

   <p>

Floats represent real numbers; they are a superset of integer numbers
but also include “numbers with decimals”. There are some limitations
when it comes to machines representing real numbers, but floating point
numbers are a good representation in most cases. You can learn more
about the specifics of floats for your runtime environment, by checking
the value of sys.float_info. This will also tell you what’s the largest
and smallest number that can be represented with them.

.. raw:: html

   </p>

.. raw:: html

   <p>

Once again, can test some examples with the type() function:

.. code:: ipython3

    # Print the type of 1.0
    
    type(1.0) # Notice that 1 is an int, and 1.0 is a float

.. code:: ipython3

    # Print the type of 0.5
    
    type(0.5)

.. code:: ipython3

    # Print the type of 0.56
    
    type(0.56)

.. code:: ipython3

    # System settings about float type
    
    sys.float_info

.. raw:: html

   <h3 id="convert">

Converting from one object type to a different object type

.. raw:: html

   </h3>

.. raw:: html

   <p>

You can change the type of the object in Python; this is called
typecasting. For example, you can convert an integer into a float
(e.g. 2 to 2.0).

.. raw:: html

   </p>

.. raw:: html

   <p>

Let’s try it:

.. raw:: html

   </p>

.. code:: ipython3

    # Verify that this is an integer
    
    type(2)

.. raw:: html

   <h4>

Converting integers to floats

.. raw:: html

   </h4>

.. raw:: html

   <p>

Let’s cast integer 2 to float:

.. raw:: html

   </p>

.. code:: ipython3

    # Convert 2 to a float
    
    float(2)

.. code:: ipython3

    # Convert integer 2 to a float and check its type
    
    type(float(2))

.. raw:: html

   <p>

When we convert an integer into a float, we don’t really change the
value (i.e., the significand) of the number. However, if we cast a float
into an integer, we could potentially lose some information. For
example, if we cast the float 1.1 to integer we will get 1 and lose the
decimal information (i.e., 0.1):

.. raw:: html

   </p>

.. code:: ipython3

    # Casting 1.1 to integer will result in loss of information
    
    int(1.1)

.. raw:: html

   <h4>

Converting from strings to integers or floats

.. raw:: html

   </h4>

.. raw:: html

   <p>

Sometimes, we can have a string that contains a number within it. If
this is the case, we can cast that string that represents a number into
an integer using int():

.. raw:: html

   </p>

.. code:: ipython3

    # Convert a string into an integer
    
    int('1')

.. raw:: html

   <p>

But if you try to do so with a string that is not a perfect match for a
number, you’ll get an error. Try the following:

.. raw:: html

   </p>

.. code:: ipython3

    # Convert a string into an integer with error
    
    int('1 or 2 people')

.. raw:: html

   <p>

You can also convert strings containing floating point numbers into
float objects:

.. raw:: html

   </p>

.. code:: ipython3

    # Convert the string "1.2" into a float
    
    float('1.2')

.. raw:: html

   <hr/>

.. container:: alert alert-success alertsuccess

   ::

      [Tip:] Note that strings can be represented with single quotes (<code>'1.2'</code>) or double quotes (<code>"1.2"</code>), but you can't mix both (e.g., <code>"1.2'</code>).

.. raw:: html

   <hr/>

.. raw:: html

   <h4>

Converting numbers to strings

.. raw:: html

   </h4>

.. raw:: html

   <p>

If we can convert strings to numbers, it is only natural to assume that
we can convert numbers to strings, right?

.. raw:: html

   </p>

.. code:: ipython3

    # Convert an integer to a string
    
    str(1)


.. raw:: html

   <p>

And there is no reason why we shouldn’t be able to make floats into
strings as well:

.. raw:: html

   </p>

.. code:: ipython3

    # Convert a float to a string
    
    str(1.2)

.. raw:: html

   <h3 id="bool">

Boolean data type

.. raw:: html

   </h3>

.. raw:: html

   <p>

Boolean is another important type in Python. An object of type Boolean
can take on one of two values: True or False:

.. raw:: html

   </p>

.. code:: ipython3

    # Value true
    
    True

.. raw:: html

   <p>

Notice that the value True has an uppercase “T”. The same is true for
False (i.e. you must use the uppercase “F”).

.. raw:: html

   </p>

.. code:: ipython3

    # Value false
    
    False

.. raw:: html

   <p>

When you ask Python to display the type of a boolean object it will show
bool which stands for boolean:

.. raw:: html

   </p>

.. code:: ipython3

    # Type of True
    
    type(True)

.. code:: ipython3

    # Type of False
    
    type(False)

.. raw:: html

   <p>

We can cast boolean objects to other data types. If we cast a boolean
with a value of True to an integer or float we will get a one. If we
cast a boolean with a value of False to an integer or float we will get
a zero. Similarly, if we cast a 1 to a Boolean, you get a True. And if
we cast a 0 to a Boolean we will get a False. Let’s give it a try:

.. raw:: html

   </p>

.. code:: ipython3

    # Convert True to int
    
    int(True)

.. code:: ipython3

    # Convert 1 to boolean
    
    bool(1)

.. code:: ipython3

    # Convert 0 to boolean
    
    bool(0)

.. code:: ipython3

    # Convert True to float
    
    float(True)

.. raw:: html

   <h3 id="exer_type">

Exercise: Types

.. raw:: html

   </h3>

.. raw:: html

   <p>

What is the data type of the result of: 6 / 2?

.. raw:: html

   </p>

.. code:: ipython3

    # Write your code below. Don't forget to press Shift+Enter to execute the cell
    type (6/2)




.. parsed-literal::

    float



.. raw:: html

   <details>

.. raw:: html

   <summary>

Click here for the solution

.. raw:: html

   </summary>

.. code:: python

   type(6/2) # float

.. raw:: html

   </details>

.. raw:: html

   <p>

What is the type of the result of: 6 // 2? (Note the double slash //.)

.. raw:: html

   </p>

.. code:: ipython3

    # Write your code below. Don't forget to press Shift+Enter to execute the cell
    type (6//2)




.. parsed-literal::

    int



.. raw:: html

   <details>

.. raw:: html

   <summary>

Click here for the solution

.. raw:: html

   </summary>

.. code:: python

   type(6//2) # int, as the double slashes stand for integer division 

.. raw:: html

   </details>

.. raw:: html

   <hr>

.. raw:: html

   <h2 id="expressions">

Expression and Variables

.. raw:: html

   </h2>

.. raw:: html

   <h3 id="exp">

Expressions

.. raw:: html

   </h3>

.. raw:: html

   <p>

Expressions in Python can include operations among compatible types
(e.g., integers and floats). For example, basic arithmetic operations
like adding multiple numbers:

.. raw:: html

   </p>

.. code:: ipython3

    # Addition operation expression
    
    43 + 60 + 16 + 41

.. raw:: html

   <p>

We can perform subtraction operations using the minus operator. In this
case the result is a negative number:

.. raw:: html

   </p>

.. code:: ipython3

    # Subtraction operation expression
    
    50 - 60

.. raw:: html

   <p>

We can do multiplication using an asterisk:

.. raw:: html

   </p>

.. code:: ipython3

    # Multiplication operation expression
    
    5 * 5

.. raw:: html

   <p>

We can also perform division with the forward slash:

.. code:: ipython3

    # Division operation expression
    
    25 / 5

.. code:: ipython3

    # Division operation expression
    
    25 / 6

.. raw:: html

   <p>

As seen in the quiz above, we can use the double slash for integer
division, where the result is rounded down to the nearest integer:

.. code:: ipython3

    # Integer division operation expression
    
    25 // 5

.. code:: ipython3

    # Integer division operation expression
    
    25 // 6

.. raw:: html

   <h3 id="exer_exp">

Exercise: Expression

.. raw:: html

   </h3>

.. raw:: html

   <p>

Let’s write an expression that calculates how many hours there are in
160 minutes:

.. code:: ipython3

    # Write your code below. Don't forget to press Shift+Enter to execute the cell
    160/60




.. parsed-literal::

    2.6666666666666665



.. raw:: html

   <details>

.. raw:: html

   <summary>

Click here for the solution

.. raw:: html

   </summary>

.. code:: python

   160/60 

   # Or 

   160//60

.. raw:: html

   </details>

.. raw:: html

   <p>

Python follows well accepted mathematical conventions when evaluating
mathematical expressions. In the following example, Python adds 30 to
the result of the multiplication (i.e., 120).

.. code:: ipython3

    # Mathematical expression
    
    30 + 2 * 60

.. raw:: html

   <p>

And just like mathematics, expressions enclosed in parentheses have
priority. So the following multiplies 32 by 60.

.. code:: ipython3

    # Mathematical expression
    
    (30 + 2) * 60

.. raw:: html

   <h3 id="var">

Variables

.. raw:: html

   </h3>

.. raw:: html

   <p>

Just like with most programming languages, we can store values in
variables, so we can use them later on. For example:

.. raw:: html

   </p>

.. code:: ipython3

    # Store value into variable
    
    x = 43 + 60 + 16 + 41

.. raw:: html

   <p>

To see the value of x in a Notebook, we can simply place it on the last
line of a cell:

.. raw:: html

   </p>

.. code:: ipython3

    # Print out the value in variable
    
    x

.. raw:: html

   <p>

We can also perform operations on x and save the result to a new
variable:

.. raw:: html

   </p>

.. code:: ipython3

    # Use another variable to store the result of the operation between variable and value
    
    y = x / 60
    y

.. raw:: html

   <p>

If we save a value to an existing variable, the new value will overwrite
the previous value:

.. raw:: html

   </p>

.. code:: ipython3

    # Overwrite variable with new value
    
    x = x / 60
    x

.. raw:: html

   <p>

It’s a good practice to use meaningful variable names, so you and others
can read the code and understand it more easily:

.. raw:: html

   </p>

.. code:: ipython3

    # Name the variables meaningfully
    
    total_min = 43 + 42 + 57 # Total length of albums in minutes
    total_min

.. code:: ipython3

    # Name the variables meaningfully
    
    total_hours = total_min / 60 # Total length of albums in hours 
    total_hours

.. raw:: html

   <p>

In the cells above we added the length of three albums in minutes and
stored it in total_min. We then divided it by 60 to calculate total
length total_hours in hours. You can also do it all at once in a single
expression, as long as you use parenthesis to add the albums length
before you divide, as shown below.

.. raw:: html

   </p>

.. code:: ipython3

    # Complicate expression
    
    total_hours = (43 + 42 + 57) / 60  # Total hours in a single expression
    total_hours

.. raw:: html

   <p>

If you’d rather have total hours as an integer, you can of course
replace the floating point division with integer division (i.e., //).

.. raw:: html

   </p>

.. raw:: html

   <h3 id="exer_exp_var">

Exercise: Expression and Variables in Python

.. raw:: html

   </h3>

.. raw:: html

   <p>

What is the value of x where x = 3 + 2 \* 2

.. raw:: html

   </p>

.. code:: ipython3

    # Write your code below. Don't forget to press Shift+Enter to execute the cell
    x=3+2*2
    


.. raw:: html

   <details>

.. raw:: html

   <summary>

Click here for the solution

.. raw:: html

   </summary>

.. code:: python

   7

.. raw:: html

   </details>

.. raw:: html

   <p>

What is the value of y where y = (3 + 2) \* 2?

.. raw:: html

   </p>

.. code:: ipython3

    # Write your code below. Don't forget to press Shift+Enter to execute the cell
    y=(3 + 2) *2

.. raw:: html

   <details>

.. raw:: html

   <summary>

Click here for the solution

.. raw:: html

   </summary>

.. code:: python

   10

.. raw:: html

   </details>

.. raw:: html

   <p>

What is the value of z where z = x + y?

.. raw:: html

   </p>

.. code:: ipython3

    # Write your code below. Don't forget to press Shift+Enter to execute the cell
    z = x + y

.. raw:: html

   <details>

.. raw:: html

   <summary>

Click here for the solution

.. raw:: html

   </summary>

.. code:: python

   17

.. raw:: html

   </details>

.. raw:: html

   <hr>

.. raw:: html

   <h2>

The last exercise!

.. raw:: html

   </h2>

.. raw:: html

   <p>

Congratulations, you have completed your first lesson and hands-on lab
in Python. However, there is one more thing you need to do. The Data
Science community encourages sharing work. The best way to share and
showcase your work is to share it on GitHub. By sharing your notebook on
GitHub you are not only building your reputation with fellow data
scientists, but you can also show it off when applying for a job. Even
though this was your first piece of work, it is never too early to start
building good habits. So, please read and follow this article to learn
how to share your work.

.. raw:: html

   <hr>

Author
------

Joseph Santarcangelo

Other contributors
------------------

Mavis Zhou

Change Log
----------

================= ======= ========== ==================================
Date (YYYY-MM-DD) Version Changed By Change Description
================= ======= ========== ==================================
2020-08-26        2.0     Lavanya    Moved lab to course repo in GitLab
\                                    
\                                    
================= ======= ========== ==================================

##

.. raw:: html

   <h3 align="center">

© IBM Corporation 2020. All rights reserved.

.. raw:: html

   <h3/>
