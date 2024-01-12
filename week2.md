Variables and Types
Exercises
Week 2
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
Which is the purpose of a variable within Python?
Answer:Resrved Memory location to store value
_________________________________________________________________________
Write a simple Python statement that creates and assigns a value of 3.142 to a variable
called ‘pi’
Answer:pi = 3.142
_________________________________________________________________________
Which of the following is NOT a valid name for a variable within Python?
total
result
question?
name_1
Answer:question?
_________________________________________________________________________
Following the execution of the code below, what will be stored in the variable 'age'?
age = 10 + 20
age = age + 5
Answer:30
In the answer box below write the exact output that would be displayed if the following
statement was executed (assuming age has been created as in the previous question):
print("The age value is",age)
Answer:35
_________________________________________________________________________
Which of the following is an example of an Augmented Assignment in Python?
total = 20
total = total + 5
total *= 100
total = max
Answer:total *=100
_________________________________________________________________________
Which of the following is an example of an integer type variable?
result = "xyz"
result = 20
result = 20.5
result = False
Answer:result = 20
_________________________________________________________________________
What are the only two legal values of a boolean type variable?
Answer: True , False
_________________________________________________________________________
Following the execution of the code below, what will be the data-type of the variable
'average'?
average = total / count
Answer: float
_________________________________________________________________________
Following the execution of the code below, what will be the data-type of the variable
'message'?
message = "hello there!"
Answer: string 
_________________________________________________________________________
What determines the current data-type of a variable?
Answer:type()
_________________________________________________________________________
What is the purpose of the built-in type() function?
Answer: determine data type
_________________________________________________________________________
What would be the output following execution of the following code?
type(10.2)
Answer:float
_________________________________________________________________________
Does the Python language support Dynamic Typing, or Static Typing?
Answer:dynamic Typing
_________________________________________________________________________
Which of the following is an example of a function call?
answer = 10
print(answer)
total *= 10
10 + 20
Answer:print(answer)
________________________________________________________________________
What is the name given to the values that are passed to a function within the parentheses?
Answer: arguments or parameters
_________________________________________________________________________
What is the purpose of the built-in input() function?
Answer:to input data by user
_________________________________________________________________________
What is the data-type of the value returned by the input() function?
Answer:string
_________________________________________________________________________
Use the Python interpreter to input a small Python program that prints your name and
address on the screen. Once this works type the program in the answer box below.
Answer:# This is a simple Python program
# that prints name and address

# Define variables
name = "Pranab"
address = "Samakhushi, kathmmandu"

# Print name and address
print("Name:", name)
print("Address:", address)

_________________________________________________________________________
Within the answer box below write a small Python program, that when run, would print the
following message including the double quotes -
Hello, is your name "Bwian"?
Answer:# This is a Python program that prints a message 
print('Hello, is your name "Bwian"?')
Now write a second small Python program, that when run, would print the following message
including the single quotes -
Or is your name 'Woger'?
Answer:# This is another Python program that prints a message
print("Or is your name 'Woger'?")
_________________________________________________________________________
Within the answer box below write a small Python program, that when run, uses escape
sequences to print the following text exactly.
This is a string containing a backslash (\),
 a single quote ('), a double quote (")
 and is split across multiple lines
Answer:# Python program using escape sequences
print("This is a string containing a backslash (\\),\n a single quote ('), a double quote (\")\n and is split across multiple lines")

_________________________________________________________________________
Within the answer box below write a small Python program, that when run, uses triple quotes
to print the following text exactly.
This is a string containing a backslash (\),
 a single quote ('), a double quote (")
 and is split across multiple lines
Answer:# Python program using triple quotes
print('''This is a string containing a backslash (\\),
a single quote ('), a double quote (")
and is split across multiple lines''')

_________________________________________________________________________
Use the Python interpreter to input a small Python program that asks the user to input a
temperature in fahrenheit. Once the value has been input, display a message that shows the
same temperature in celsius. You may have to do some research in order to find out the
conversion method. Once this works, type the program in the answer box below.
Answer:# Python program for Fahrenheit to Celsius conversion

# Get temperature in Fahrenheit from the user
fahrenheit = float(input("Enter temperature in Fahrenheit: "))

# Convert Fahrenheit to Celsius
celsius = (fahrenheit - 32) * 5/9

# Display the result
print(f"The temperature in Celsius is: {celsius:.2f}°C")

_________________________________________________________________________
Within the answer box below write a small Python program that asks the user to enter two
values. Store these in variables called 'a' and 'b' respectively.
Answer:
Once the values have been input use three calls to the print() function to show output
such as the following (in this example the user entered 10.2 and 18.3) -
The value 'a' was 10.2 and the value 'b' was 18.3
The sum of 'a' and 'b' is 28.5
The product of 'a' and 'b' is 186.66
Answer:
# Python program to get two values from the user and perform calculations

# Get values from the user
a = float(input("Enter the value for 'a': "))
b = float(input("Enter the value for 'b': "))

# Calculate sum and product
sum_result = a + b
product_result = a * b

# Display the output
print(f"The value 'a' is {a} and the value 'b' is {b}")
print(f"The sum of 'a' and 'b' is {sum_result:.2f}")
print(f"The product of 'a' and 'b' is {product_result:.2f}")

________________________________________________________________________
Python includes a built-in function called max(). When this is called with multiple argument
values it returns the largest of the given arguments. e.g.
max(20, 50, 30) # this would return 50
Within the answer box below write a small program that asks the user to input three values.
Store these in variables (the names are up to you) then use the max() function to display the
largest of the input values.
Answer:
Using the Python interpreter execute your code, then examine the output generated when
the input the values are 'hello', 'welcome', and 'bye'
Does the program still show the maximum value? If not, what does it show?
Answer:
# Python program to find the largest of three input values

# Get values from the user
value1 = input("Enter the first value: ")
value2 = input("Enter the second value: ")
value3 = input("Enter the third value: ")

# Use max() function to find the largest value
largest_value = max(value1, value2, value3)

# Display the result
print(f"The largest value is: {largest_value}")

_________________________________________________________________________
Given the following definition:
name = "Black Knight"
What would each of the following Python statements display?
print( name[0] )
Answer:
print( name[4] )
Answer:
print( name[-1] )
Answer:
print( name[-2] )
Answer:
print( name[2:5] )
Answer:
print( name[6:] )
Answer:
print( name[:5] )
Answer:
print( name[:] )
Answer:name = "Black Knight"

# Display the first character of the string
print(name[0])
# Output: B

# Display the fifth character of the string
print(name[4])
# Output: k

# Display the last character of the string
print(name[-1])
# Output: t

# Display the second-to-last character of the string
print(name[-2])
# Output: h

# Display characters from index 2 to 4 (excluding 5)
print(name[2:5])
# Output: ack

# Display characters starting from index 6 to the end
print(name[6:])
# Output: Knight

# Display characters from the beginning to index 4 (excluding 5)
print(name[:5])
# Output: Black

# Display the entire string
print(name[:])
# Output: Black Knight

_________________________________________________________________________
Which of the following creates a variable containing a List?
names = "Terry"
names = 10
names = [ "Mark", "Jon", "Amanda", "Edward", "Sally" ]
names = "Mark", "Jon", "Amanda"
Answer:names = [ "Mark", "Jon", "Amanda", "Edward", "Sally" ]

_________________________________________________________________________
Is the following a valid List, even though it contains values based on different data-types?
values = [10.2, "Jon", False, "Edward", True ]
Answer:yes
_________________________________________________________________________
If a value is mutable, can it be modified after it has been created?
Answer:yes
_________________________________________________________________________
What term is used to describe a value that cannot be changed once it has been created?
Answer:immutable
_________________________________________________________________________
Is a List mutable or immutable?
Answer:mutable
_________________________________________________________________________
Is a String mutable or immutable?
Answer:immutable
_________________________________________________________________________
Given the following definition -
names = ["Terry", "John", "Michael", "Eric", "Terry", "Graham"]
What would each of the following Python statements display?
print( names[2] )
Answer:Michael
print( names[-2] )
Answer:Terry
print( names[0:3] )
Answer:['Terry', 'John', 'Michael']
names = names + "Brian"
print( names )
Answer:['Terry', 'John', 'Michael', 'Eric', 'Terry', 'Graham', 'B', 'r', 'i', 'a', 'n']
names[0:1] = ["Mark", "Jon"]
print( names )
Answer:['Mark', 'Jon', 'John', 'Michael', 'Eric', 'Terry', 'Graham', 'B', 'r', 'i', 'a', 'n']
_________________________________________________________________________
What built-in function within Python can be used to find out how many elements are
contained within a string or list?
Answer:len()
_________________________________________________________________________
Exercises are complete
Save this logbook with your answers. Then ask your tutor to check your responses to each
question.