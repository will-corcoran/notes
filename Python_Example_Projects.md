# 🐍 Example Projects 🚀

## Table of Contents
1. [Drawing a Shape](#drawing-a-shape)
2. [Building a Basic Calculator](#building-a-basic-calculator)
3. [Mad Libs Game](#mad-libs-game)
4. [Building a Better Calculator](#building-a-better-calculator)
5. [Building a Guessing Game](#building-a-guessing-game)

## Drawing a Shape
- **Objective**: Write a basic Python program to draw a shape on the screen.
- **Method**: Utilize print statements to output a triangle shape.
- **Execution**: Python executes the print statements in order, creating a visual representation of a triangle.

- **Solution Code**:
```python
 print("/\\")
  print("/  \\")
  print("/    \\")
  print("/______\\")
```

## Building a Basic Calculator
- **Goal**: Create a simple calculator that adds two user-input numbers.
- **Process**:
  - Get two numbers from the user.
  - Convert the input from strings to numbers.
  - Add the numbers and print the result.
- **Challenges**: Addressing Python's default behavior of treating input as strings.

- **Solution Code**:
```python
num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))
result = num1 + num2
print("The sum is: " + str(result))
```

## Mad Libs Game
- **Concept**: Develop a Mad Libs game where users input words to complete a story.
- **Implementation**:
  - Prompt the user for various types of words (e.g., color, plural noun, celebrity).
  - Insert these words into a pre-defined story template.
- **Example**: Modify a classic poem with user inputs to create humorous outcomes.

- **Solution Code**:
```python
color = input("Enter a color: ")
plural_noun = input("Enter a plural noun: ")
celebrity = input("Enter a celebrity: ")
print("Roses are " + color)
print(plural_noun + " are blue")
print("I love " + celebrity)
```

## Building a Better Calculator
- **Objective**: Enhance the basic calculator to handle addition, subtraction, multiplication, and division.
- **Features**:
  - Allow the user to choose the operation.
  - Perform the chosen arithmetic operation on two user-input numbers.
- **User Input Handling**: Use if statements to determine the operation based on user input.

- **Solution Code**:
```python
num1 = float(input("Enter first number: "))
op = input("Enter operator: ")
num2 = float(input("Enter second number: "))

if op == "+":
    print(num1 + num2)
elif op == "-":
    print(num1 - num2)
elif op == "*":
    print(num1 * num2)
elif op == "/":
    print(num1 / num2)
else:
    print("Invalid operator")
```

## Building a Guessing Game
- **Game Concept**: Create a game where the user guesses a secret word.
- **Functionality**:
  - Store a secret word in the program.
  - Allow the user to input guesses.
  - Continue prompting for guesses until the user guesses the secret word correctly.

- **Solution Code**:
```python
secret_word = "giraffe"
guess = ""
while guess != secret_word:
    guess = input("Enter guess: ")
print("You win!")
```
