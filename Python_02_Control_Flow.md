# 🐍 Control Flow ⚙️

## Table of Contents
1. [List Functions](#list-functions)
2. [Functions](#functions)
3. [Return Statement](#return-statement)
4. [If Statements](#if-statements)
5. [If Statements & Comparisons](#if-statements--comparisons)
6. [While Loops](#while-loops)
7. [For Loops](#for-loops)
8. [Exponent Function](#exponent-function)
9. [2D Lists & Nested Loops](#2d-lists--nested-loops)

## List Functions
- **Introduction**: Lists are crucial for storing and organizing data in Python.
- **Extend Function**: Combines two lists (`friends.extend(lucky_numbers)`).
- **Append Function**: Adds an individual element to the end of a list (`friends.append('Creed')`).
- **Insert Function**: Inserts an element at a specified index (`friends.insert(1, 'Kelly')`).
- **Remove Function**: Removes a specific element from the list (`friends.remove('Jim')`).
- **Clear Function**: Empties the list (`friends.clear()`).
- **Pop Function**: Removes the last element from the list (`friends.pop()`).
- **Index Function**: Finds the index of an element (`friends.index('Kevin')`).
- **Count Function**: Counts the number of occurrences of an element (`friends.count('Jim')`).
- **Sort Function**: Sorts the list in ascending order (`friends.sort()`).
- **Reverse Function**: Reverses the order of the list (`lucky_numbers.reverse()`).
- **Copy Function**: Creates a copy of the list (`friends2 = friends.copy()`).

## Functions
- **Definition**: A function is a collection of code that performs a specific task.
- **Creating a Function**: Use the `def` keyword followed by the function name and parentheses.
- **Calling a Function**: Execute the function by typing its name followed by parentheses (`say_hi()`).
- **Parameters**: Functions can take parameters to receive information (`def say_hi(name, age)`).
- **Multiple Parameters**: Functions can have multiple parameters for more complex tasks.

## Return Statement
- **Purpose**: Used to return information from a function.
- **Usage**: Place `return` followed by the value or expression to return.
- **Example**: A function to cube a number (`def cube(num): return num * num * num`).
- **Storing Return Value**: Store the returned value in a variable (`result = cube(4)`).

## If Statements
- **Purpose**: Allow programs to make decisions based on conditions.
- **Basic Structure**: Execute code when certain conditions are true.
- **Example**:
  ```python
  if is_hungry:
      eat_breakfast()


## While Loops
- **Functionality**: Execute a block of code repeatedly as long as a condition is true.
- **Loop Condition**: The loop continues as long as the condition remains true.
- **Incrementing**: Often involves incrementing a variable each iteration.


- **Example**:
  ```python
  i = 1
    while i <= 10:
        print(i)
        i += 1
    print("Done with loop")

## For Loops
- **Purpose**: Loop over collections of items, like arrays or strings.

- **Syntax**:
  ```python
  for item in collection:
    # actions to perform

- **Examples**:
    - Looping through a string to print each letter.
    - Looping through an array to print each element.
    - Using `range()` to loop through a series of numbers.


## Exponent Function
- **Functionality**: Create a function to raise a number to a specific power.
- **Creating the Function**:
```python
def raise_to_power(base_num, power_num):
    result = 1
    for index in range(power_num):
        result = result * base_num
    return result
```

- **Usage**: Call the function with a base number and a power number.

## 2D Lists & Nested Loops
- **2D Lists**: Lists where each element is also a list, creating a grid-like structure.
- **Accessing Elements**: Use row and column indices to access specific elements.
- **Nested For Loops**: Use a for loop inside another for loop to iterate over 2D lists.

- **Example**:
```python
number_grid = [[1, 2, 3], [4, 5, 6], [7, 8, 9], [0]]
for row in number_grid:
    for col in row:
        print(col)
```