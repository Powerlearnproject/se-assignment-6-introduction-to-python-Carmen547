[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15322734&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.
Python is an interpreted, high-level programming language that incorporates simplified and easy-to-read syntax that makes it easy for developers to handle any type of project. Some of Python's key features that make it popular among developers include:
Easy to learn and use: Python is easy to code as it uses English like statements; this makes it ideal for use as a programming language for novices as well as the most skilled programmers.
Interpreted nature: Python code can be run as soon as it is written and this is not a small comfort in performance of concept rapid prototyping.
Cross-platform compatibility: The use of Python is possible on the Windows, MAC, and Linux operation systems and Raspberry Pi.
Extensive standard library: Python has an extensive set of built-in libraries with predefined functions on areas like file operations, numerical, scientific, statistics, machine learning on airy web and GUIs.
Dynamic typing: In python, the variables do not need to be declared as they are capable of converting to any data type depending on the information that one wants to store in them.
Object-oriented programming: Python has OOP concepts and coding, enabling methodologies filled with scale-up or scale-out replications.
Python is particularly effective in the following use cases:Python is particularly effective in the following use cases:
Web development: Web development and APIs in particular use Python, as some frameworks, such as Django and Flask, indicate.
Data analysis and visualization: Additional libraries like NumPy, Pandas, Matplotlib make it easy for engineers making use of Python to analyze data and visualize.
Machine learning and artificial intelligence: Often due to its features and the availability of different frameworks that it can utilize such as TensorFlow and scikit-learn, Python is preferred as the language to write the machine learning models and AI algorithms.
Automation and scripting: Python is a very good language because it is easy to read and use, it is a good language to automate processes or even writing system scripts.
Scientific and mathematical computing.Python has become the go-to language for scientific computations, numerical analysis, and more with the help of its libraries SciPy (<bz> and SymPy.
Example:
print("Hello, World!")
REFERENCES
Python, The Python Tutorial, https://docs.python.org/3/tutorial/, Accessed on 24 June 2024
Geeks for Geeks,Learn Python Basics, https://www.geeksforgeeks.org/python-basics/, Accessed on 24 June 2024
2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.
   To install Python, follow these steps:
1.	Go to the official Python download page at https://www.python.org/downloads/,  At downloads choose the latest version of Python for your system  either windows, mac os or Linux
2.	Install Python for Windows Download the Python installer 64-bit or 32 bit depending on your system architecture run the installer by double-clicking the downloaded file follow the prompts to install Python ensure you select the options to install the launcher for all users and add Python to the path for mac os and Linux download the python installer from the official website run the installer by double clicking the downloaded file follow the prompts to install python.
3.	Verify Python installation open a command prompt or terminal type Python version to confirm that Python has been installed correctly.
4.	Set up Python environment for beginners it is recommended to install Python from the Microsoft store on Windows this method handles path settings for the current user and provides automatic updates. For more advanced users you can download and install Python directly from the official website which allows more control over the installation process.
5.	Choose an integrated development environment ide popular choices include py charm visual studio code and ide each has its own features and user interface so choose the one that best suits your needs.
6.	 Write and run Python code use your chosen ide to write and run python code for simple programs you can also use a text editor like Notepad and run the code from the command prompt.
By following these steps you will have Python installed on your system and be ready to start building and executing your code.
REFERENCES
Geeks for Geeks, How to install Python on Windows?, https://www.geeksforgeeks.org/how-to-install-python-on-windows/, Accessed on 24 June 2024
Python, Python Releases For Windows,https://www.python.org/downloads/windows/, Accessed on 24 June  2024


3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.
Python program that prints "Hello, World!" to the console, along with an explanation of the basic syntax elements used:Python program that prints "Hello, World!" to the console, along with an explanation of the basic syntax elements used:      print("Hello, World!") 
Function call: The print() function is an integrated function in python used for printing data returned to the command line. The operation “print(“Hello, World!”)” is to call the interpreter to print the “Hello, World!” out on the console by making a call to the function print().
String: The text ‘Hello, World!’ is a string, which is a data type that’s used when processing text in Python. Such a string in Python can be enclosed in single quote (’), double quote (“), or triple quotes (””).
Whitespace: Python uses spaces, tabs, and new lines very significantly to structure the code and determine how to execute it. Here, the use of the print() function does not require indentation, as the function itself is at the highest level of the code.
Semicolon: In Python just like the other programming languages, semicolon (;) is not needed to end a statement. The statement print("Hello, World!") has no semicolon, yet it is a syntactically correct instruction.
When you run this Python program, the output will be:
Hello, World!

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.
   Entities used to store and manipulate values in the Python programming language
Integers (int): Integers to include both positive and negative numbers without any fractional component; for example, whole numbers are 42 and -17.
Floating-point numbers (float): Decimal numbers are those numbers having decimal point in their writing, for example 3. 14 or -2. 5.
Strings (str): Strings of characters; Signs that combine symbols enclosed in quotation marks, including “Hello, World!” and ‘42’.
Booleans (bool): True/False with respect to the applied logic in relational databases.
There are other data types in python including lists, tuples, dictionary, and sets which are used for storing more than one value.
We invest some time in declaring variables of various data types and show how one can actually set up values the variables as well as display the variable’s contents. These tables output the values of each type of variable as a representation of possible data types in Python.
Note here that the Python is a dynamically typed language hence it does not require the programmer to declare the data type of different variables. Examples of simple variable types include integers, floating point numbers, characters, and Booleans where the type is defined by the value assigned to the variable.
An example:
# Integer
age = 25
print("Age:", age)  # Output: Age: 25

# Float
pi = 3.14159
print("Pi:", pi)  # Output: Pi: 3.14159

# String
name = "John Doe"
print("Name:", name)  # Output: Name: John Doe

# Boolean
is_student = True
print("Is Student:", is_student)  # Output: Is Student: True

# List
fruits = ["apple", "banana", "cherry"]
print("Fruits:", fruits)  # Output: Fruits: ['apple', 'banana', 'cherry']

# Tuple
point = (3, 4)
print("Point:", point)  # Output: Point: (3, 4)

# Dictionary
person = {"name": "John", "age": 30, "city": "New York"}
print("Person:", person)  # Output: Person: {'name': 'John', 'age': 30, 'city': 'New York'}

# Set
colors = {"red", "green", "blue"}
print("Colors:", colors)  # Output: Colors: {'green', 'blue', 'red'}
REFERENCES:
Python,Data Types,https://docs.python.org/3/library/datatypes.html, Accessed on 24 June 2024
w3schools,Python Data Types,https://www.w3schools.com/python/python_datatypes.asp, Accesssed on 24 June 2024



5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.
   Compensation statements in Python programming language, for instance, if-else statement helps you to execute different segments of code in a given condition. The general syntax is:
   if condition:
    # code block executed if condition is True
else:
    # code block executed if condition is False
Example:
age = 18
if age >= 18:
    print("You are an adult.")
else:
    print("You are a minor.")

    Loops in python are used to work through data sets and make decisions based on a certain circumstance, and can be used to Repeat a block of code. The for loop is used to loop over the sequence of elements ( a list, tuple, string) or any other objects which supports iteration.
The general syntax for a for loop is:The general syntax for a for loop is:
for item in sequence:
    # code block executed for each item in the sequence
    An Example:
    Kpop Music = ["Hype Boy", "Dynamite", "Monster"]
for kpop music for kpop:
    print("I like", kpop)
    REFERENCES:
    Stackoveflow, Control structures beyond standard conditionals and loop?, https://stackoverflow.com/questions/6887295/control-structures-beyond-standard-conditionals-and-loops, Accessed on 24 June 2024
    Statistical Programmin Methods, https://smac-group.github.io/ds/control.html, Accessed on 24 June 2024


6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.
   Functions in Python are reusable blocks of code that perform a specific task. They are useful for the following reasons:
   Code Reuse: Functions allow for writing code once and using it in any part of the program, making its maintenance easy.

Modularity: Functions enable breaking down your program into smaller chunks that are more easily understood, debugged and modified.

Abstraction: Functions abstract away the details of implementation so that you focus on what your program is supposed to do in a more general sense.

Parameterization: Function can take arguments (parameters) that help you modify them and make very flexible.
an example of a Python function that takes two arguments and returns their sum:
python
def add_numbers(a, b):
    """
    Adds two numbers and returns the result.

    Args:
        a (int or float): The first number to add.
        b (int or float): The second number to add.

    Returns:
        int or float: The sum of the two numbers.
    """
    result = a + b
    return result

# Example usage
x = 5
y = 10
sum_of_numbers = add_numbers(x, y)
print(sum_of_numbers)  # Output: 15
Breakdown of the function:
The def keyword is used to define the function.
The function name is add_numbers.
The function takes two arguments: a and b.
The function body contains the logic to add the two numbers and store the result in the result variable.
The return statement is used to send the result back to the caller.
The function is called with the arguments x and y, and the result is stored in the sum_of_numbers variable.
The print() function is used to display the result.
Functions in Python are super useful for organizing and reusing your code. They're like the secret sauce for writing clean, modular, and easy-to-maintain programs. You can think of functions as mini-programmers that you can call whenever you need them. They make your code more organized and your life as a programmer way easier. 
REFERENCES
Free Learning Platform For Better Future, Control structures in Python, https://www.javatpoint.com/control-structures-in-python, Accessed on 24 June 2024


7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.
Lists vs. Dictionaries: 

When it comes to data structures, you've got two main options: lists and dictionaries

Lists: Think of lists as ordered collections of items, where each item has its own index. You can access items in a list by referring to their index, like "my_list[3]".

Dictionaries: On the other hand, dictionaries are unordered collections of key-value pairs. Instead of using indexes, you access values in a dictionary by their corresponding keys. For example, if you have a dictionary called "my_dict", you can access a value by typing "my_dict['key']".

Uniqueness: Now, here's an important distinction. Lists can have duplicate values. So if you need to store multiple instances of the same value, a list is your go-to. On the other hand, dictionaries require unique keys, but their values can be duplicates. This makes dictionaries handy when you want to associate specific information with each key.

Mutability: Both lists and dictionaries are mutable, meaning you can add, remove, or modify elements to your heart's content. Need to add a new element to a list or dictionary? No problem. Want to remove something or change a value.
An example:
# List of numbers
numbers = [5, 2, 8, 1, 9]

# Dictionary with key-value pairs
person = {
    "name": "John Doe",
    "age": 35,
    "city": "New York"
}

# List operations
print("List:", numbers)
print("Length of the list:", len(numbers))
print("Second element in the list:", numbers[1])
numbers.append(7)
print("List after appending:", numbers)
numbers.remove(2)
print("List after removing an element:", numbers)

# Dictionary operations
print("\nDictionary:", person)
print("Value of the 'name' key:", person["name"])
person["occupation"] = "Engineer"
print("Dictionary after adding a new key-value pair:", person)
del person["age"]
print("Dictionary after removing a key-value pair:", person)

Output:
List: [5, 2, 8, 1, 9]
Length of the list: 5
Second element in the list: 2
List after appending: [5, 2, 8, 1, 9, 7]
List after removing an element: [5, 8, 1, 9, 7]

Dictionary: {'name': 'John Doe', 'age': 35, 'city': 'New York'}
Value of the 'name' key: John Doe
Dictionary after adding a new key-value pair: {'name': 'John Doe', 'age': 35, 'city': 'New York', 'occupation': 'Engineer'}
Dictionary after removing a key-value pair: {'name': 'John Doe', 'city': 'New York', 'occupation': 'Engineer'}

So there you have it, a rundown of lists and dictionaries. Each has its own unique characteristics and use cases, so choose the one that fits your needs best. 
When it comes to lists and dictionaries, there are a few key differences you should know. First off, lists are all about keeping things in a specific order, while dictionaries don't really care about the order at all. Lists are made up of individual items, while dictionaries are more like pairs of things, where each item has a unique "key" and a corresponding "value".
REFERENCES
Stackoverflow,What does Python treat as reference types?,https://stackoverflow.com/questions/6158907/what-does-python-treat-as-reference-types, Accessed on 24 June 2024



8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.
In Python, you can manage surprises or special issues that pop up when a program runs using something called exception handling. By guessing and taking care of possible mistakes, your code gets stronger and more dependable.
The basic structure of exception handling in Python uses the following keywords:
try: This block contains the code that might raise an exception.
except: This block handles the exception that was raised in the try block.
finally: This block is executed regardless of whether an exception was raised or not.
Example:
try:
    # This code might raise an exception
    result = 10 / 0
    print(result)
except ZeroDivisionError:
    # This block handles the ZeroDivisionError exception
    print("Error: Division by zero")
finally:
    # This block is always executed, regardless of whether an exception was raised or not
    print("This is the finally block")

print("Program execution continues...")
Output:
Error: Division by zero
This is the finally block
Program execution continues...
REFERENCES:
Stackoverflow,Is it a good practice to use try-except-else in Python?,https://stackoverflow.com/questions/16138232/is-it-a-good-practice-to-use-try-except-else-in-python, Accessed on 24 June 2024
9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.
   Modules
A code block is a document with Python commands and explanations. It makes grouping similar code simpler aiding in better control and recycling. Inside, functions, types, and variables you can reach from different code parts live.
Example:
To use a module in your script, you can import it using the import statement. 
python
import math

# Using functions from the math module
print(math.pi)  # Output: 3.141592653589793
print(math.sqrt(16))  # Output: 4.0
from math import pi, sqrt

print(pi)  # Output: 3.141592653589793
print(sqrt(16))  # Output: 4.0
Packages let you sort modules into levels, like sorting papers and folders on your computer. A package has many modules and it puts together ones that are similar.
To make a package, make a folder with the name you want for the package. Then put the module files (the Python scripts) in that folder. You also have to add a special file named init.py to your package folder. This file can be empty. However, it has to be there to show the folder is a package.
Example:
my_package/
    __init__.py
    math_utils.py
    string_utils.py
REFERENCES:
w3schools,Python Data Types,https://www.w3schools.com/python/python_datatypes.asp, Accesssed on 24 June 2024

10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.
To read the contents of a file in Python, you can use the open() function to open the file, and then use the read() method to read the contents. Here's an example:
python
Example:
# Open the file in read mode
with open('example.txt', 'r') as file:
    # Read the contents of the file
    content = file.read()

# Print the contents to the console
print(content)

In this example, we use the with statement to open the file 'example.txt' in read mode ('r'). The with statement ensures that the file is properly closed after we're done with it, even if an exception occurs.
The read() method reads the entire contents of the file and stores it in the content variable. Finally, we print the contents to the console.

To write to a file in Python, you can use the open() function to open the file in write mode, and then use the write() method to write the data to the file. Here's an example:
python
Example:

# Open the file in write mode
with open('output.txt', 'w') as file:
    # Write a list of strings to the file
    lines = ['Hello, world!', 'This is a test.', 'Goodbye!']
    for line in lines:
        file.write(line + '\n')

In this example, we open the file 'output.txt' in write mode ('w'). We then create a list of strings and use a for loop to write each string to the file, followed by a newline character ('\n').
After running this script, a new file named 'output.txt' will be created in the same directory, containing the following content:
Hello, world!
This is a test.
Goodbye!
REFERENCES:
W3schools,Python File Open,https://www.w3schools.com/python/python_file_handling.asp,Accessed on 24 June 2024

# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


