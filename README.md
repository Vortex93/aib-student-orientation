# Lesson 1: Variables in Python

## Introduction
In this assignment, you will learn about variables in Python and how to use them to store and manipulate data.

### Tasks
1. Create a Python program that declares three variables: `name`, `age`, and `country`.
2. Assign appropriate values to each variable. For example, `name` could be your name, `age` could be your age in years, and `country` could be your country of residence.
3. Print the values of the variables to the console using the `print()` function.
4. Write a comment explaining the purpose of each variable.

```python
# Variable Declarations
name    = "John Doe"
age     = 20
country = "Aruba"

# Printing Variable Values
print("Name   :", name)
print("Age    :", age)
print("Country:", country)
```

### Output Output
```
Name: John Doe
Age: 20
Country: Aruba
```


In this sample code, three variables are declared: `name`, `age`, and `country`. Appropriate values are assigned to each variable. The `print()` function is then used to display the values of the variables to the console.

You can copy this code into your Python file and run it to see the output with the assigned values. Feel free to modify the values or add any additional code as needed to test your understanding of variables in Python.

---

# Lesson 2: Functions in Python

## Introduction
In this lesson, you will learn how to define and use functions in Python.

### Tasks
1. Create a Python program that defines a function called `greet()` without any parameters.
2. Inside the `greet()` function, print a greeting message, such as "Hello, welcome to the world of programming!"
3. Call the `greet()` function outside its definition to execute it.
4. Write a comment explaining the purpose of the `greet()` function.

In this script, a function called `greet()` is defined without any parameters. Inside the function, a greeting message is printed to the console. The `greet()` function is then called outside its definition to execute it and display the greeting message.

You can copy this script into your Python file and run it to see the output. The greeting message will be displayed as "Hello, welcome to the world of programming at AIB!". Feel free to modify the message or add any additional code as needed.

```python
# Function Definition
def greet():
    print("Hello, welcome to the world of programming at AIB!")

# Calling the greet() function
greet()
```

### Output
```
Hello, welcome to the world of programming at AIB!
```

---

# Lesson 3: Loops in Python

## Introduction
In this lesson, you will learn how to use for loops in Python to iterate over a sequence of elements.

### Tasks
1. Create a Python program that uses a for loop to iterate over the elements of a list containing the numbers 1 to 5.
2. Inside the loop, print each number on a separate line.
3. Write a comment explaining the purpose of the for loop.

```python
# List of Numbers
numbers = [1, 2, 3, 4, 5]

# For Loop to Print Numbers
for number in numbers:
    print(number)
```

### Output
```
1
2
3
4
5
```

---

# Lesson 4: Working with Lists in Python

## Introduction
In this lesson, you will learn how to work with lists in Python, which allow you to store and manipulate multiple values in a single variable.

### Tasks
1. Create a Python program that defines a list called `fruits` containing the names of three fruits.
2. Access and print the second fruit in the list.
3. Add a new fruit to the end of the list.
4. Update the value of the first fruit in the list.
5. Write a comment explaining the purpose of each step.

```python
# List of Fruits
fruits = ["apple", "banana", "orange"]

# Accessing and Printing a Fruit
print("Second Fruit:", fruits[1])

# Adding a New Fruit
fruits.append("grape")

# Updating a Fruit
fruits[0] = "strawberry"

# Printing the Updated List of Fruits
print("Updated Fruits:", fruits)
```

### Output
```
Second Fruit: banana
Updated Fruits: ['strawberry', 'banana', 'orange', 'grape']
```

---

# Lesson 5: Conditional Statements in Python

## Introduction
In this lesson, you will learn how to use conditional statements in Python to make decisions based on certain conditions.

### Tasks
1. Create a Python program that asks the user to enter their age.
2. Store the user's input in a variable.
3. Use an if statement to check if the user is above 18 years old.
4. If the user is above 18, print a message saying they are eligible to vote. Otherwise, print a message saying they are not eligible to vote.
5. Write a comment explaining the purpose of each step.

```python
# User Input
age = int(input("Enter your age: "))

# Eligibility Check
if age >= 18:
    print("You are eligible to vote!")
else:
    print("You are not eligible to vote.")
```

### Output
```
Enter your age: 22
You are eligible to vote!
```

---

# Lesson 6: User Input in Python

## Introduction
In this lesson, you will learn how to take user input in Python and use it in your programs.

### Tasks
1. Create a Python program that asks the user to enter their name.
2. Store the user's input in a variable.
3. Print a personalized greeting message using the user's name.
4. Write a comment explaining the purpose of each step.

```python
# User Input
name = input("Enter your name: ")

# Greeting Message
print("Hello, " + name + "!")

# Note: You can also use f-string formatting for the greeting message
# print(f"Hello, {name}!")
```

### Output
```
Enter your name: John
Hello, John!
```

### Explanation
In this lesson, we use the `input()` function to take user input. The `input()` function prompts the user to enter their name, and the user's input is stored in the `name` variable. We then print a greeting message using the user's name by concatenating it with a predefined string. You can also use f-string formatting to achieve the same result by placing the variable name within curly braces `{}` in the print statement.

---








# Assignment 1: Printing a Christmas Tree

## Introduction
In this assignment, you will apply your knowledge of variables, functions, and for loops in Python to generate and print a Christmas tree pattern using asterisks and spaces.

### Tasks
1. Create a Python program that prompts the user for the number of rows for the Christmas tree and generates the corresponding pattern.
2. Implement the logic to generate the Christmas tree pattern using nested for loops and conditional statements.
3. Print the resulting pattern to the console.
4. Write a comment explaining the purpose of each section of code.

### Example Output
```
Enter the number of rows for the tree: 5

        *
       ***
      *****
     *******
    *********
```

---

# Assignment 2: Temperature Converter

## Introduction
In this assignment, you will practice using variables and arithmetic operations in Python by creating a temperature converter.

### Tasks
1. Create a Python program that asks the user to enter a temperature in Celsius.
2. Store the user's input in a variable.
3. Convert the temperature from Celsius to Fahrenheit using the formula: `F = (C * 9/5) + 32`, where `F` is the temperature in Fahrenheit and `C` is the temperature in Celsius.
4. Print the converted temperature in Fahrenheit.
5. Write a comment explaining the purpose of each step.

### Example output
```
Enter temperature in Celsius: 25
Temperature in Fahrenheit: 77.0
```

---

# Assignment 3: Sum of Digits

## Introduction
In this assignment, you will practice using variables, loops, and arithmetic operations in Python by creating a program that calculates the sum of digits in a given number.

### Tasks
1. Create a Python program that asks the user to enter a positive integer.
2. Store the user's input in a variable.
3. Use a loop and arithmetic operations to calculate the sum of the digits in the number.
4. Print the sum of the digits.
5. Write a comment explaining the purpose of each step.

### Example output
```
Enter a positive integer: 12345
Sum of Digits: 15
```

---

Certainly! Here are the modified assignments starting from Assignment 4 onwards:

---

# Assignment 4: Leap Year Checker

## Introduction
In this assignment, you will create a program that determines whether a given year is a leap year or not using conditional statements in Python.

### Tasks
1. Create a Python program that asks the user to enter a year.
2. Store the user's input in a variable.
3. Use an if statement and the leap year formula to check if the year is a leap year.
4. Print a message indicating whether the year is a leap year or not.
5. Write a comment explaining the purpose of each step.

### Guidance
- A leap year is a year that is exactly divisible by 4, except for years that are divisible by 100.
- However, years that are divisible by 400 are leap years.

### Example Output
```
Enter a year: 2020

The year is a leap year.
```

---

# Assignment 5: Sum of Digits

## Introduction
In this assignment, you will practice using variables, loops, and arithmetic operations in Python by creating a program that calculates the sum of digits in a given number.

### Tasks
1. Create a Python program that asks the user to enter a positive integer.
2. Store the user's input in a variable.
3. Use a loop and arithmetic operations to calculate the sum of the digits in the number.
4. Print the sum of the digits.
5. Write a comment explaining the purpose of each step.

### Example output
```
Enter a positive integer: 12345
Sum of Digits: 15
```

---

# Assignment 6: User Input in Python

## Introduction
In this assignment, you will learn how to take user input in Python and use it in your programs.

### Tasks
1. Create a Python program that asks the user to enter their name.
2. Store the user's input in a variable.
3. Print a personalized greeting message using the user's name.
4. Write a comment explaining the purpose of each step.

### Example Output
```
Enter your name: John
Hello, John!
```

### Explanation
In this lesson, we use the `input()` function to take user input. The `input()` function prompts the user to enter their name, and the user's input is stored in the `name` variable. We then print a greeting message using the user's name.

---

# Assignment 7: Conditional Statements in Python

## Introduction
In this assignment, you will learn how to use conditional statements in Python to make decisions based on certain conditions.

### Tasks
1. Create a Python program that asks the user to enter their age.
2. Store the user's input in a variable.
3. Use an if statement to check if the user is above 18 years old.
4. If the user is above 18, print a message saying they are eligible to vote. Otherwise, print a message saying they are not eligible to vote.
5. Write a comment explaining the purpose of each step.

### Example Output
```
Enter your age: 22
You are eligible to vote!
```

---

## Submission Instructions

Please follow the instructions below to submit your completed assignments.

1. Save your Python code for each assignment in separate files with the following filenames:
   - Assignment 1: `assignment_1.py`
   - Assignment 2: `assignment_2.py`
   - Assignment 3: `assignment_3.py`

2. Once you have completed the assignments and saved the files, please come to me (Derwin) to show what you have done.

3. During the submission, I will review your code and execute it to see if it functions properly.

Please make sure to complete the assignments and be prepared to present your code for review. If you have any questions or need further assistance, please don't hesitate to ask.