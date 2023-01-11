# Python

## A word about python

---

Python is a high-level, interpreted programming language. It was created by Guido van Rossum and first released in 1991. Python is known for its simple and easy-to-read syntax, making it a great language for beginners to learn. It also has a large and supportive community, with a wealth of libraries and frameworks available for use in a variety of applications, such as web development, scientific computing, data analysis, artificial intelligence, and more.

One of the key features of Python is that it is a dynamically typed language, which means that the type of a variable is determined at runtime, rather than being explicitly specified when the variable is declared. This makes Python very flexible and allows for rapid development, but can also make the code more prone to errors.

Python also has built-in support for object-oriented programming (OOP) which is a programming paradigm based on the concept of "objects" which have properties and methods. This allow to write reusable, maintainable and extensible code.

Python is available for a wide variety of platforms, including Windows, macOS, and Linux. It can be run using an interpreter, or can be compiled to a standalone executable. It is commonly used in many industries such as finance, healthcare, retail, and many more.

## What will you learn by reading this

---

0. **[Variables](##Variables)** and **[Data types](##Data-types)**: Learn about different data types in Python, such as integers, strings, and floating-point numbers, and how to store them in variables.
    0. **[Variables](##Variables)**
    1. **[Data types](##Data-types)**
        0. **[Numbers](###Numbers)**
            0. **[Integers](###Integers)**
            1. **[Floats](###Floats)**

1. **Operators**: Learn about the various operators in Python, including arithmetic operators, comparison operators, and logical operators, and how to use them to perform calculations and compare values.

2. **Flow control**: Learn about control flow statements in Python, such as if-else statements, for and while loops, and how to use them to control the flow of a program.

3. **Lists** and **dictionaries**: Learn about two of the most commonly used data structures in Python: lists, which are used to store ordered collections of items, and dictionaries, which are used to store key-value pairs.

4. **Functions**: Learn how to define and use functions to organize and reuse code in a program.

5. **Reading** and **Writing files**: Learn how to read and write files in python using open method, reading methods and writing methods

6. **Errors** and **Exception handling**: Learn how to handle errors and exceptions that may occur while a program is running, and how to use try-except statements to handle them.

7. **Modules**: Learn how to import and use modules from Python's standard library, as well as how to create your own modules.

These are just a few examples of the many things you can learn when starting with Python. The language is very powerful and has many libraries that can be used in various field like machine learning, data analysis, web scraping, data visualization etc.

# Variables and data types

## Variables

---

In Python, a variable is a named location in memory that is used to store a value. The value stored in a variable can be of various types, such as an integer, a string, a floating-point number, and so on.

> Declaring a variable in Python is done using the assignment operator (=), with the variable name on the left side and the value to be stored in the variable on the right side.

For example:

```python
x = 5
name = "Alice"
is_ok = True
```

Here, `x` is a variable of type int and holding value 5, `name` is a variable of type str and holding value "Alice", `is_ok` is a variable of type bool and holding value True

In Python, variable names can contain letters, numbers, and underscores, but must start with a letter or an underscore. They are case sensitive, meaning that **‘name’** and **‘Name’** would be treated as two different variables.

One thing to note is that in Python, you don't need to explicitly specify the data type of a variable, the data type will be determined by the value assigned to it.

Python also has a feature called "garbage collection" that automatically frees up memory that is no longer being used by the program. This means that you do not need to explicitly delete a variable or free up its memory.

You can also assign multiple variables at once by separating them with a comma:

```python
x, y = 5, 8
```

It is good practice to use meaningful and self-explanatory variable names, as well as to use proper naming conventions such as snake_case or camelCase. This can make your code more readable and understandable for others who may need to work on it in the future.

## Data types

---

### Numbers

---

In Python, numbers are used to represent numeric values and are stored as integer or floating-point values.

#### Integers

---

In Python, an integer is a whole number that can be positive, negative, or zero. They are represented by the int data type and can be created using literals, which are numeric constants. Here are some examples of integer literals:

```python
x = 5   # a positive integer
y = -3  # a negative integer
z = 0   # zero
```

Integers in Python can be also represented in different bases such as binary, octal, and hexadecimal, which are denoted by prefix **‘0b’**, **‘0o’**, **‘0x’** respectively. For example:

```python
binary_num = 0b1010     # binary representation of 10
octal_num = 0o777       # octal representation of 511
hexadecimal_num = 0xFF  # hexadecimal representation of 255
```

Integers in Python are objects, they have their own methods such as **‘bit_length()’** which will return the number of bits required to represent an integer in binary:

```python
x = 5
print(x.bit_length())   # 3
```

Integers in Python also support a number of mathematical operations such as addition, subtraction, multiplication, and division, as well as more advanced mathematical functions. Here are some examples:

```python
x = 5
y = 2
print(x + y)    # 7
print(x - y)    # 3
print(x * y)    # 10
print(x / y)    # 2.5
print(x // y)   # 2
print(x % y)    # 1
print(x ** y)   # 25
```

> In Python, integers have no fixed maximum or minimum value and can be of any size.

Unlike other programming languages that might have a fixed-size range. Python is designed to handle large integers and supports arbitrarily large integers, limited only by the amount of memory available in the system. Python can handle integers of any size as long as there is enough memory to store them.

In practice, the maximum and minimum values of integers are determined by the amount of memory allocated for storing them on a specific system. The value of maximum or minimum integers could be **_2^31-1_** and **_-2^31_** respectively on a 32-bit system and **_2^63-1_** and **_-2^63_** respectively on a 64-bit system. However, due to the abstract nature of the Python's int type, these limits do not exist in practice and you can use int class for large integers and decimal module for decimal precision integers.

Python also has built-in support for arbitrary precision integers using the **‘decimal’** module. These integers can have a very large number of digits, and are useful for financial or monetary calculations where the exact decimal representation is important.

#### Floats

---
