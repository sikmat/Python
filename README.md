# WEEK-1
# DAY 1 - 3

Indentation is very important in python compared to java that I'm more familiar of. Statements that go together must have the same indentation. Wrong indentation causes errors.
PyCharm and VScode automate indentation, making it easier and offer more support for python 

Portable
Python code is portable due to it being interpreted rather than compiled, which would require the code to be first converted to binary code(0s and 1s) using a complier. When you run the program the linker would first have to  copy the code from disk to memory. 
Python does not need the code to be compiled to binary, it converts to the code into bytecode and translated it into the native language of the computer. 
Supports procedure-oriented programming - program is built around procedures or functios (reusable pieces of programs).
Supports OOP - programs built around objects which combine data and functionality. 
Strings are immutable in Python?
String formating in Python is cleaner.
Concatenation is not neat and is error prone.
String conversion is done automatically by the format method, Ie. Create variable and assign it a value which you then call with its index. Assign those variables as arguments the format method. Can also use named parameters using f-strings, all you do is place letter f before the string Ex: (f'{name} was {age} years old')
Does literal constants mean I cannot write numbers purely as a String? *Interesting*
Boolean NOT negates True to False and False to True.
Boolean AND (x and y) returns False if x is False, else it returns y. 
Boolean OR, if x is True returns True, else returns evaluation of 
Floor division //

# DAY 4
SETS: are usefull for removing duplicates from a list because they can only contain unique values and their order is randomized. Their elements cannot be accessed with index or slicing syntax. 
Explored sets union and how duplicates can be removed using examples from https://realpython.com/python-sets/

TUPLES: are also similar to List but declared with parenthesis() instead of square brackets[], but can also be without parenthesis. They cannot be modified, elements can be accessed via index. Take up less memory, usefull    for storing large amounts of data compared to lists. Also useful for returning multiple values from a a function.

DICTIONARIES: work with Key-Value pairs. import defaultdict from collections package, it easier to work with. defaultdict creates a new default value if a key doesn't exist yet, instead returning an error. You must specify   the type of object you want returned.

LIST COMPREHENSIONS: enclosed in square brackets. Enables you to filter or apply functions to every item in the list. They are useful for cleaning string and handling large datasets

LIST COMPREHENSIONS with FUNCTIONS
SPLIT Function: Allows you to split a string based on a given character or string, using a period as a delimiter or spaces if there is no delimiter available. The string is then separated from the period. 
To remove periods and apply lowercase we can create a function which uses "replace" and "lower" functions to remove periods and convert string to lowercase

DICTIONARIES & COMPREHENSIONS
Can create new dictionary from an iterable structure using comprehensions.

# DAY 5
If Else: Python uses "elif" for "else if"
While loops: Code can run forever if not provided a break statement to exit from the loop and move to the next line of code. Continue statement is useful for skipping over lines that come after the continue statement. Continue can be used inside if statement to stop some code in the loop from running. Continue and break can also be used for rearanging code and making it neat.
For Loop: You can declare a variable that will hold the value of each element as you go through the list. 
Pass: Used as a stub

# WEEK-2
# DAY 1

FUNCTIONS
Consists of name and parameters(created with "def" keyword). after "def comes an identifier name followed by a pair of parentheses whic may enclose variable names. A function is a reusable piece of a program, allowing you to run the specific block of code using the specified name by "calling the function".

NAMED PARAMETERS: (OR Keyword arguments) Used to assign a default value to the operation parameter.
Parameters and Arguments mean the same thing, information that is passed into a function. 
Function must be called with correct number of args, not more, not less.

*args: Use a * before parameter name if you do not know how many args to pass on to a function, but this only works for positional arguments, not keyword arguments.

**kwargs: Is a method used to handle keyword arguments. Keyword args get stored as a dictionary instead of tuple because they have keys and values can be passed in any order. 

VARIABLES & SCOPE

Locals(): Variables that are only accessible locally within a function. Trying to access a variable outside its scope results in an error.

Globals(): Defined outside the function, in the main code block. Allows for access of many items including Python pre-built variables

Python checks the local scope first for a variable, before moving to check the global scope. We can also redefine a variable that is local and global so it we can print both the local and global data.

We can also declare a function within another function, the inner function can only be called within the function it is declared in. Calling it outside will result in an error
A function is represented as an object.
Think of Functions as some variables that are associated with some data

Create Python Text Processing Functions to clean text.(Important in businesses, for processing text)

Lambda Functions: Used to represent a function without giving it a variable name(lambda x: x + 3)(5), the return key is implied. Handy for passing a function as an argument to another Python function.
An underscore is used as a variable name to indicate that the variable is not used.

# DAY 2
ANATOMY OF A CLASS
Static Attributes: Defining a static variable outside of a constructor means each instance will share the same values. Static variables don't change with each instance and are commonly used to hold constants or important business logic. They can still be changed, so to prevent this programmers add an underscore before the variable name(indicating the variable should not be modified directly, a getter method should be used instead).
A getter method retreives the value of th variable, without passing in the self attribute because the variable is static.

# DAY 3


# DAY 4


# DAY 5


