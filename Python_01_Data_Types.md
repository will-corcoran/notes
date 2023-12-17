# 🐍 Variables & Data Types 📊

# Table of Contents
1. [Variables & Data Types](#variables--data-types)
2. [Working With Strings](#working-with-strings)
3. [Working With Numbers](#working-with-numbers)
4. [Lists](#lists)
5. [Tuples](#tuples)
6. [Dictionaries](#dictionaries)
7. [Sets](#sets)
8. [Boolean Type](#boolean-type)
9. [None Type](#none-type)
10. [Type Conversion](#type-conversion)
11. [Mutable vs Immutable Types](#mutable-vs-immutable-types)
12. [File Handling](#file-handling)



## Variables & Data Types
- **Definition of Variables**: Containers for storing data values.
- **Purpose**: Simplify data management in programs.
- **Creating Variables**: Assign a name and value using the equals sign (`=`).
  - Example: 
    ```python
    character_name = "John"
    character_age = "35"
    ```
- **Using Variables**: Replace specific text in a program, making it dynamic.
- **Concatenating Variables with Text**: Use the plus sign (`+`) for concatenation.
- **Benefits of Variables**: Flexibility, readability, and efficiency in data management.
- **Data Types**: Strings, numbers (integers, floats), and Booleans (True/False).

## Working With Strings
- **Introduction to Strings**: Strings are plain text data.
- **Creating Strings**: Use quotation marks (`" "`) to define a string.
- **String Functions**:
  - `.lower()`: Converts string to lowercase.
  - `.upper()`: Converts string to uppercase.
  - `.isupper()`: Checks if the string is in uppercase.
  - `len()`: Returns the length of the string.
  - Indexing: Access characters using square brackets and index (e.g., `phrase[0]`).
  - `.index()`: Finds the index of a substring or character.
  - `.replace()`: Replaces part of the string with another string.
- **Special Characters in Strings**:
  - New Line: `\n` creates a new line.
  - Quotation Mark: `\"` to include a quotation mark inside a string.
  - Backslash: `\\` to include a backslash in the string.
- **Concatenation**: Combining strings using the plus sign (`+`).
- **String Variables**: Storing strings in variables for easy access and modification.

## Working With Numbers
- **Basics**: Numbers are a common data type in Python, used in most programs.
- **Printing Numbers**: Can print whole, decimal, and negative numbers.
- **Arithmetic Operations**: Addition, subtraction, multiplication, division, and modulus.
- **Order of Operations**: Use parentheses to specify the order.
- **Modulus Operator**: `%` sign used for modulus operation, returns the remainder.
- **Storing in Variables**: Numbers can be stored in variables.
- **Converting to String**: Use `str()` to convert numbers to strings for printing.
- **Math Functions**:
  - `abs()`: Absolute value.
  - `pow()`: Raises a number to a specific power.
  - `max()`: Returns the larger of two numbers.
  - `min()`: Returns the smaller of two numbers.
  - `round()`: Rounds a number to the nearest whole number.
- **Importing Math Module**: Use `from math import *` to access more math functions.
- **Advanced Math Functions**:
  - `floor()`: Rounds down to the nearest whole number.
  - `ceil()`: Rounds up to the nearest whole number.
  - `sqrt()`: Calculates the square root.

## Lists
- **Introduction**: Lists store multiple values and are essential for managing data.
- **Creating Lists**: Use square brackets `[]` to create and store values.
- **Accessing Elements**: Refer to elements by their index.
- **Modifying Elements**: Elements can be modified by their index.
- **Selecting Portions**: Use slicing to select portions of the list.
- **Modifying Values**: Change values by referring to their index.

## Tuples
- **Basics**: Similar to lists but immutable (cannot be changed).
- **Creating Tuples**: Use parentheses `()` to create tuples.
- **Use Case**: Ideal for data that does not need to change, like coordinates.
- **Accessing Elements**: Access elements by their index.
- **Immutability**: Cannot modify, add, or delete elements in a tuple.
- **Lists vs. Tuples**: Lists are mutable and more commonly used; tuples are for unchangeable data.


## Dictionaries
- **Introduction to Dictionaries**: Explain how dictionaries store data in key-value pairs.
- **Creating Dictionaries**: Demonstrate how to create and initialize dictionaries.
- **Accessing and Modifying Data**: Show how to retrieve, add, modify, and delete data in dictionaries.
- **Iterating Over Dictionaries**: Discuss methods to loop through keys, values, or key-value pairs.

## Sets
- **Basics of Sets**: Describe sets as collections of unique elements.
- **Creating Sets**: Illustrate how to create sets and add elements.
- **Set Operations**: Introduce operations like union, intersection, difference, and symmetric difference.

## Boolean Type
- **Understanding Booleans**: Explain the Boolean data type with its two values: True and False.
- **Usage in Conditions**: Show how Booleans are used in control flow statements (if, while).

## None Type
- **Purpose of None**: Describe the None type, used to represent the absence of a value.
- **Common Use Cases**: Explain scenarios where None is commonly used, such as initializing variables or indicating special conditions.

## Type Conversion
- **Implicit and Explicit Conversion**: Discuss the difference between implicit (automatic) and explicit (manual) type conversion.
- **Common Functions for Conversion**: Include examples using `int()`, `float()`, `str()`, etc.

## Mutable vs Immutable Types
- **Explanation**: Clarify the difference between mutable (modifiable) and immutable (non-modifiable) data types.
- **Examples**: Provide examples of each type and explain their implications in Python programming.

## File Handling
- **Basics of File Operations**: Introduce how to open, read, write, and close files in Python.
- **Context Managers**: Explain the use of `with` statement for efficient file handling.
