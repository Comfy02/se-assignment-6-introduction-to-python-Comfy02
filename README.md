[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15317438&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

📍Python is a high-level, interpreted programming language known for its simplicity, readability, and large community. Key features include:

- Easy-to-learn syntax
- Cross-platform compatibility
- Extensive libraries and frameworks

Use cases: web development, data analysis, machine learning, automation, scientific computing.

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

   📍- Windows: Download from chrome, run the installer, and follow prompts.
- macOS (with Homebrew): brew install python
- Linux: apt-get install python (Ubuntu-based) or yum install python (RPM-based)

Verify installation: Open a terminal/command prompt and type python --version. Set up a virtual environment using venv.

3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

   📍Simple "Hello, World!" program:

print("Hello, World!")

Basic syntax elements:

- print(): a function that outputs text
- "Hello, World!": a string literal
- () : parentheses for function calls

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

📍Basic data types:

- Integers (int): x = 5
- Floats (float): y = 3.14
- Strings (str): name = "John"
- Boolean (bool): is_admin = True

Script demonstrating variables:

x = 5
y = 3.14
name = "John"
is_admin = True
print(x, y, name, is_admin)

5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

   📍Conditional statements:

x = 5
if x > 10:
    print("x is greater than 10")
else:
    print("x is less than or equal to 10")

Loops:

fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(fruit)

6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

   📍A Python function that takes two arguments and returns their sum:

def add(x, y):
    return x + y
result = add(3, 5)
print(result)  # Output: 8

7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

   📍Lists:

- Ordered collections of items
- Indexed by integers (0-based)
- Can contain duplicate values
- Can be modified (mutable)

Dictionaries:

- Unordered collections of key-value pairs
- Keys must be unique and immutable
- Values can be any type
- Can be modified (mutable)

Script:

# List
numbers = [1, 2, 3, 4, 5]
print(numbers[0])  # Output: 1
numbers.append(6)
print(numbers)  # Output: [1, 2, 3, 4, 5, 6]

# Dictionary
person = {"name": "John", "age": 30, "city": "New York"}
print(person["name"])  # Output: John
person["country"] = "USA"
print(person)  # Output: {"name": "John", "age": 30, "city": "New York", "country": "USA"}


8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

   📍Exception handling in Python:

- try block: code that might raise an error
- except block: code to handle the error
- finally block: code to execute regardless of an error

Example:

try:
    x = 5 / 0
except ZeroDivisionError:
    print("Error: cannot divide by zero!")
finally:
    print("This code always runs")

9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

   📍Modules:

- Pre-written code that can be imported and used
- Can be a single file or a package (directory with multiple files)

Packages:

- Directories with multiple modules and a __(link unavailable) file

Importing and using a module:

import math
print(math.pi)  # Output: 3.14159

10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

    📍Reading from a file:

with open("example.txt", "r") as file:
    content = file.read()
print(content)  # Output: the content of the file

Writing to a file:

fruits = ["apple", "banana", "cherry"]
with open("fruits.txt", "w") as file:
    for fruit in fruits:
        file.write(fruit + "\n")


# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


