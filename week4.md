Functions
Exercises
Week 4
Prior to attempting these exercises ensure you have read the lecture notes and/or viewed
the video, and followed the practical. You may wish to use the Python interpreter in
interactive mode to help work out the solutions to some of the questions.
Download and store this document within your own filespace, so the contents can be edited.
You will be able to refer to it during the test in Week 6.
Enter your answers directly into the highlighted boxes.
For more information about the module delivery, assessment and feedback please refer to
the module within the MyBeckett portal.
_________________________________________________________________________
©2021 Mark Dixon / Tony Jenkins
_________________________________________________________________________
What must be done before a function that is not built-in to Python can be used in a program?
Answer:Function must be imported if not built in
_________________________________________________________________________
Given the following import statement, how would a call to the sin() function be made?
import math
Answer:From math import sin
_________________________________________________________________________
Given the following import statement, how would a call to the sqrt() function be made?
from math import sqrt
Answer:
From math import sqrt
number = 25
result= sqrt(number)

_________________________________________________________________________
What is the name of the common library that is available with all Python distributions?
Answer:common library
_________________________________________________________________________
What keyword is used in Python to define a new function?
Answer:def
_________________________________________________________________________
Write some Python code that defines a function called print_header(msg). This should
output the value provided by the ‘msg’ parameter to the screen (prefixed by five asterisk
‘*****’) characters.
Answer:
def print_header(msg):
    header="***" + str(msg)
    print(header)
_________________________________________________________________________
In the answer box below give an example of what the docstring may look like for the
print_header(msg) function.
Answer:def print_header(msg):
    '''defining the function'''
_________________________________________________________________________
Where within a function definition should a docstring appear?
Answer:First statement
_________________________________________________________________________
What statement should appear within a function’s code block to cause a specific value to be
passed back to the caller of the function?
Answer:return
_________________________________________________________________________
Write some Python code that defines a function called find_min(a,b) that returns the
smallest of the two given parameter values.
Answer:
def find_min(a, b):
    """
    Returns the smallest of the two given parameter values.

    Parameters:
    a (int or float): First parameter.
    b (int or float): Second parameter.

    Returns:
    int or float: The smallest value between a and b.
    """
    return min(a, b)

# Example usage:
result = find_min(5, 10)
print("The minimum value is:", result)

_________________________________________________________________________
Given the following function definition, which of the formal parameters could be described as
being a default argument?
def shouldContinue(prompt, answer=False):
# function body...
Answer:answer
Provide two example calls to the above function, one which provides a value for the default
argument, and one that does not.
Answer:
_________________________________________________________________________
State why following function definition would not be allowed.
def do_something(prefix="Message", prompt, answer=False):
# function body...
Answer:The default argument (prefix) must come after non-default arguments (prompt) in a function signature.
_________________________________________________________________________
What single character is placed directly before the name of a formal parameter, to indicate
that a variable number of actual parameters can be passed when the function is called?
Answer:*
_________________________________________________________________________
What commonly used built-in function, which displays output on the screen, can take a
variable number of arguments?
Answer:print()
_________________________________________________________________________
Is it valid for a function’s parameter name to be prefixed by two asterisk characters ‘**’ as
shown below?
def send_output(**details):
# function body...
Answer:yes
If present, what does this prefix indicate?
Answer:Keyword arguments
_________________________________________________________________________
What is the name given to a small ‘anonymous’ function that must be defined using a single
expression?
Answer:lambda
Give an example of such a function that calculates the cube of a given number (i.e. the value
of the number raised to the power of three) -
Answer:
cube=lambda x: x**3
result = cube(4)
print(result)
_________________________________________________________________________
Exercises are complete
Save this logbook with your answers. Then ask your tutor to check your responses to each
question.