# Learning python from zero

## A word about python

---

Python is a high-level, interpreted programming language. It was created by Guido van Rossum and first released in 1991. Python is known for its simple and easy-to-read syntax, making it a great language for beginners to learn. It also has a large and supportive community, with a wealth of libraries and frameworks available for use in a variety of applications, such as web development, scientific computing, data analysis, artificial intelligence, and more.

One of the key features of Python is that it is a dynamically typed language, which means that the type of a variable is determined at runtime, rather than being explicitly specified when the variable is declared. This makes Python very flexible and allows for rapid development, but can also make the code more prone to errors.

Python also has built-in support for object-oriented programming (OOP) which is a programming paradigm based on the concept of "objects" which have properties and methods. This allow to write reusable, maintainable and extensible code.

Python is available for a wide variety of platforms, including Windows, macOS, and Linux. It can be run using an interpreter, or can be compiled to a standalone executable. It is commonly used in many industries such as finance, healthcare, retail, and many more.

## What will you learn by reading this

---

1. **[Basic info about "Python from zero"](##Basic-info-about-"Python-from-zero")**: Learn about what we will cover in this course.
    1. **[Comments](##Comments)**
    2. **[Print](##Print)**
1. **[Variables and data types](#Variables-and-data-types)**: Learn about different data types in Python, such as integers, strings, and floating-point numbers, and how to store them in variables.
    1. **[Variables](##Variables)**
    2. **[Data types](##Data-types)**
        1. **[Numbers](###Numbers)**
            1. **[Integers](###Integers)**
            2. **[Floats](###Floats)**
1. **Operators**: Learn about the various operators in Python, including arithmetic operators, comparison operators, and logical operators, and how to use them to perform calculations and compare values.

1. **Flow control**: Learn about control flow statements in Python, such as if-else statements, for and while loops, and how to use them to control the flow of a program.

1. **Lists** and **dictionaries**: Learn about two of the most commonly used data structures in Python: lists, which are used to store ordered collections of items, and dictionaries, which are used to store key-value pairs.

1. **Functions**: Learn how to define and use functions to organize and reuse code in a program.

1. **Reading** and **Writing files**: Learn how to read and write files in python using open method, reading methods and writing methods

1. **Errors** and **Exception handling**: Learn how to handle errors and exceptions that may occur while a program is running, and how to use try-except statements to handle them.

1. **Modules**: Learn how to import and use modules from Python's standard library, as well as how to create your own modules.

These are just a few examples of the many things you can learn when starting with Python. The language is very powerful and has many libraries that can be used in various field like machine learning, data analysis, web scraping, data visualization etc.

# Basic info about "Python from zero"

In a **"python from zero"** self-teacher course, it's essential to start with the basics of the language.

Python is a high-level programming language that is easy to learn and use, making it a great choice for beginners. Some of the basics of Python that you will likely cover in the course include:

1. Data types: Python has several built-in data types, including integers, floating-point numbers, strings, and booleans. You will teach people how to create variables, assign values to them, and work with different data types.

2. Basic operations: You will cover basic arithmetic operations such as addition, subtraction, multiplication, and division, and how to use comparison and logical operators.

3. Flow control: Teach people about control statements like if-else statements, for and while loops and how to control the flow of the program.

4. Functions: You will show how to use functions in Python, how to define them, how to call them and how to return values from them.

As you are learning, we will use comments near the print statements to show the output, to make sure that you understand the output of each piece of code we are working with and to confirm that the code is working as expected.

This way, you will have a clear understanding of the basics of Python and will be able to start building simple programs right away.

## Comments

---

In Python, comments are used to add human-readable explanations, documentation or remarks to the source code of a program. Comments are ignored by the Python interpreter, meaning that they have no effect on the execution of the program.

There are two types of comments in Python:

1. Single-line comments, which begin with the **`#`** character and continue to the end of the line. For example:

```python
# This is a single-line comment

x = 5   # This is also a single-line comment
```

2. Multi-line comments, which are used to comment out a block of code or a large text, and are defined using triple quotation marks **`'''`** or **`"""`**. For example:

```python
'''
This is a
multiline
comment
'''

"""
And this is
also a multiline
comment
"""
```

Using comments in your code is considered a best practice. Comments are used to explain what the code is doing and make it more readable, also help other people who will read or work with your code to understand it better. Additionally, comments can be used to document the purpose, usage, and expected behavior of functions, classes, and modules in your codebase.

It is true that you will use comments very often in the course. Because commenting your code will help to make it more understandable, more maintainable, and more likely to be useful to others.

When you write a program or a piece of code, you may want to print the value of certain variables or the results of certain calculations in order to check that your code is working as expected.

> Placing comments near a print statement can help to explain what the output represents and what it is supposed to be.

For example:

```python
x = 5
y = 2
print(x + y)    # 7
```

The comments after the print statement show the expected output of **_7_**, which confirms that the code is functioning as expected.

Another use case can be for debugging, when you want to print intermediate values during the execution of the code to understand how the program is functioning.

This way, you can easily understand what the printed output should be, so you can quickly check if the code is working correctly.

Additionally, having comments to explain what the printed statement is doing, it will help you or other people understand the code better, especially when you come back to it after a while.

## Print

---

The ‘`print()`’ statement is a built-in function in Python that is used to output text or data to the console or other output devices. The ‘`print()`’ function takes one or more expressions as its arguments, which can be of any data type, such as strings, numbers, or variables.

Here is an example of a basic ‘`print()`’ statement:

```python
print("Hello, World!")
```

This will output the string `"Hello, World!"` to the console.

You can also use the print() function to print the value of variables or the result of an expression:

```python
x = 5
y = 2
print(x + y)
```

This will output the value of ‘`x + y`’, which is **7**, to the console.

You can also use multiple arguments and separate them with a comma, which will separate the output with spaces:

```python
print("The value of x is:", x)
```

This will output `"The value of x is: 5"`

The print function is very versatile, and is used very often in Python programming, it's used in debugging, displaying the output, displaying errors, and much more.

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

Here, ‘`x`‘ is a variable of type int and holding value 5, ‘`name`‘ is a variable of type str and holding value `"Alice"`, `is_ok` is a variable of type bool and holding value True

In Python, variable names can contain letters, numbers, and underscores, but must start with a letter or an underscore. They are case sensitive, meaning that ‘`name`’ and ‘`Name`’ would be treated as two different variables.

One thing to note is that in Python, you don't need to explicitly specify the data type of a variable, the data type will be determined by the value assigned to it.

Python also has a feature called "garbage collection" that automatically frees up memory that is no longer being used by the program. This means that you do not need to explicitly delete a variable or free up its memory.

You can also assign multiple variables at once by separating them with a comma:

```python
x, y = 5, 8
```

> Good variable naming is an important aspect of writing clean and readable code.

It helps to make the code more self-explanatory, which makes it easier to understand and maintain.

Here are some general guidelines for good variable naming in Python:

1. Use meaningful and descriptive names: Use variable names that clearly indicate the purpose of the variable and the type of data it holds. For example, use ‘`name`’ for a string variable that holds a person's name, and ‘`age`’ for an integer variable that holds a person's age.

2. Be consistent with naming conventions: Python uses the conventions of snake_case for variable, function and method names and PascalCase for class names. It's a good practice to stick to one naming convention and apply it consistently throughout the codebase.

3. Avoid using single-letter variable names: Single-letter variable names can make it difficult to understand the purpose of the variable, especially if the codebase is large. Instead, use more descriptive names that give an idea of what the variable represents.

4. Avoid using reserved keywords: Python has a set of reserved keywords that cannot be used as variable names. These keywords include words like ‘`if`’, ‘`else`’, ‘`while`’, ‘`for`’, ‘`class`’, ‘`def`’, ‘`True`’, ‘`False`’, ‘`None`’ etc.

## Data types

---

### Numbers

---

In Python, numbers are used to represent numeric values and are stored as integer or floating-point values.

#### Integers

---

In Python, an integer is a whole number that can be positive, negative, or zero.

> In Python, an integer can be defined using numeric literals.

A numeric literal is a value that is written directly in the source code of a program. For example:

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

In Python, a float is a numeric type that represents a real number with a decimal point. Floats are used to represent numbers with fractional parts, such as **_3.14_** or **_2.718_**. They are represented by the float data type and can be created using literals, which are numeric constants. Here are some examples of float literals:

> In Python, a floating-point number can be defined using a decimal point.

A decimal point is used to indicate that a number is a floating-point number. For example:

```python
a = 3.14
b = -2.718
c = 4.0
```

You can also define a floating-point number using scientific notation, using the letter **‘e’** or **‘E’** to indicate the power of **_10_**. For example, the number **_0.000034_** can be represented as **_3.4e-5_** or **_3.4E-5_**. Here are some examples:

```python
d = 3.4e-2  # 3.4 x 10^-2 = 0.034
e = 2.8e5   # 2.8 x 10^5 = 280000.0
```

Like integers, floats in Python can be also used in mathematical operations such as addition, subtraction, multiplication, and division:

```python
x = 3.14
y = 2.718
print(x + y)    # 5.858
print(x - y)    # 0.422
print(x * y)    # 8.52772
print(x / y)    # 1.1596606797749978
```

Floats in Python also support a number of built-in functions such as **‘round()’**, **‘math.ceil()’**, **‘math.floor()’** and **‘math.isclose()’** (to check if the two float numbers are close to each other).

It's worth noting that floating-point numbers are approximations, and thus may not always be precise. The precision of a float depends on the number of bits used to represent the number, and in Python, it uses the standard double-precision format, which is 64 bits, or 8 bytes. This format provides a precision of about 15-17 decimal digits.

Additionally, due to the way that floating-point numbers are represented in computers, some mathematical operations involving floating-point numbers may produce unexpected results because of the round-off errors.
