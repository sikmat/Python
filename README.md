# Python-Week-1 Notes
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

