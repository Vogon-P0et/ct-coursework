# Python

## Python Basics - Variables, Data Types, and Operations
Variables:
Explain variables as containers for storing data.
Demonstrate how to declare variables and assign values.
name = "John"
age = 25
height = 5.9
Data Types:
Introduce basic data types in Python: integers, floats, strings, and booleans.
age = 25        # Integer
height = 5.9    # Float
name = "Alice"  # String
is_student = True  # Boolean
Operations:
Arithmetic operations (+, -, *, /, **, %).
Comparison operations (==, !=, >, <, >=, <=).
Example:
result = 10 + 5
comparison = 5 > 3
Input/Output:
Show how to accept input from the user and display output.
name = input("What is your name? ")
print(f"Hello, {name}!")


🧠📓Engage & Apply: Create a program that takes your name, age, and favorite color as an input and prints them out.
# Expected Output:
# --> "Christian"
# --> "99"
# --> "Purple"
Control Structures - If Statements
Introduction to Control Flow:
Programs can make decisions using if, else, and elif.
Syntax of if statements:
if condition:
    # code block
elif condition:
    # code block
else:
    # code block
Example:
age = int(input("Enter your age: "))

if age >= 18:
    print("You are an adult.")
else:
    print("You are a minor.")
Nested If Statements and Multiple Conditions:
Introduce and/or logical operators.
age = int(input("Enter your age: "))

if age > 0 and age < 13:
    print("You are a child.")
elif age >= 13 and age < 20:
    print("You are a teenager.")
else:
    print("You are an adult.")


👾💻 Final Challenge: Build a program that asks the user to input their exam score and then prints a message.
Outputs should be as follows:

"Excellent" if the score is greater than 90.
"Good" if the score is between 70 and 90.
"Needs Improvement" if the score is below 70.

