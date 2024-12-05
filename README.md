# Python-for-beginners
# Python for Beginners

## Summary
This tutorial is designed to introduce beginners to the basics of Python programming. By the end of this tutorial, learners will understand basic python concepts such as variables, data types, loops, and functions.

## Target Audience
This tutorial is for people new to programming, with no prior experience needed. It’s perfect for beginners who want to learn Python.

---

### Table of Contents

1. [Introduction](#introduction)
2. [Setting Up Python](#setting-up-python)
3. [Hello, World!](#hello-world)
4. [Variables and Data Types](#variables-and-data-types)
5. [If Statements](#if-statements)
6. [Loops](#loops)
7. [Functions](#functions)
8. [Conclusion](#conclusion)


---

### 1. Introduction

Python is known for being one of the most simple programming languages,  making it the perfect option for beginner programmers! Following this tutorial will guide you through the basics of the language, and help you write your first lines of code.

---

### 2. Setting Up Python

To start programming in Python, you can either install Python directly on your computer or use Thonny, a beginner-friendly Python IDE (Integrated Development Environment). Thonny comes with Python pre-installed, so you only have to complete one download, and it's great for beginners!

#### Step 1: Download Thonny
- Go to the [official Thonny website](https://thonny.org/).
- Click on the “Download” button. The website should automatically suggest the version compatible with your operating system.

#### Step 2: Install Thonny
- Open the downloaded installer.
- Follow the prompts to install Thonny. Since Thonny comes with Python included, you won’t need to install anything else.

#### Step 3: Verify Installation
To check if Thonny is installed correctly, open the Thonny application. You should see a window with a Python shell where you can start writing your code!

---

### 3. Hello, World!

It is tradition that the first program  every beginner writes is the "Hello, World!" program. This simple program prints the text “Hello, World!” to the screen. It’s a great way to get started with understanding how Python works.

#### Step 1: Open Thonny
- Launch the Thonny application you installed in the previous section.

#### Step 2: Write the Code
In the Thonny editor, type the following code:
  print("Hello, World!")
Once you hit run (the green play button) the results should be visible in the shell.
---

### 4. Variables and Data Types

In Python, variables are used to store information, and data types tell us what kind of information that variable holds. A variable in python is basically just a label for something. Python makes it easy to use variables, and it even automatically decides the type of data based on what you put inside. These are the most common data types in Python:
  String: A sequence of characters, used to represent text. You create a string by surrounding text with quotes (" " or ' ').
    Example: "Alice"
  Integer: A whole number, without a decimal point.
    Example: 25
Float: A number with a decimal point.
    Example: 5.7

To create a variable in Python, you simply assign a value to a name using an =
  for example:
    name = "Alice"
    age = 25
you can also print them together with the line "print(name,age)"

---
### 5. If Statements

An if statement allows you to execute certain code under specific conditions. If the condition isn’t true, the code inside the if statement is skipped. This is how you can make decisions inside the program.

Here’s the basic syntax for an if statement:
  if **whatever the condition is**:
      # Code to execute if the condition is true
For example, let’s check if variable x is greater than 10:
  if x > 10:
      print("x is greater than 10!")
If you have multiple conditions to check, you can also add an **elif** or **else** statement
For example:
  if x > 10:
      print("x is greater than 10!")
  elif x == 10:
      print("x is exactly 10!")
  else:
      print("x is less than 10.")
Now you can have a different display message for each outcome!

---
### 6. Loops

Loops allow you to execute the same block of code multiple times. This can save a lot of time and effort, especially when dealing with repetitive tasks.
There are multiple different types of loops to work with in python, but **for loops** and **while loops** are best for beginners.
A **for loop** is used when you want to iterate over a sequence (like a list or range of numbers).
Here’s a basic example of a for loop:

for i in range(5):
    print(i)

output:
    0
    1
    2
    3
    4
This loop will print the numbers 0 through 4, as the end of the range is 5.

A **while loop** repeats a block of code as long as a condition is true. Here’s an example:
  count = 0
  while count < 5:
      print(count)
      count += 1
output:
  0
  1
  2
  3
  4

In this example, the loop will keep running as long as count is less than 5. Each time the loop runs, count is increased by 1.

---

### 7. Functions

Functions are reusable blocks of code that you can call multiple times in your program. They allow you to organize your code into much smaller, manageable pieces.

#### Step 1: Defining a Function
To define a function in Python, use the keyword "def" followed by the function name and parentheses. Here’s an example of a simple function:

  def hello():
      print("Hello, World!")
once you've written a function, you can call it at anytime like this
input:
  hello()
output:
  Hello, World!
  
---

### 8. Conclusion

Congratulations on completing my Python for Beginners tutorial! 

By now, you should have a basic understanding of the following Python concepts:

How to set up Python on your computer.
Writing your first Python program (Hello, World!).
Using variables and understanding data types.
Making decisions with if statements.
Repeating actions with loops.
Organizing your code with functions.

You should be able to use all of these skills to create an abundance of programs. Happy Coding!
