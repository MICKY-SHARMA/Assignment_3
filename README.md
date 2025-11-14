
 🐍 Python Programming Tasks

 📝 *Overview*

This mini Python project contains two beginner-friendly tasks designed to strengthen your understanding of *functions, **recursion, **loops, and the **math module*.

📘 *Task 1: Calculate Factorial Using a Function*
🧩 *Problem Statement*

Write a Python program that:

1. Defines a function named factorial that takes a number as an argument and calculates its factorial using a *loop* or *recursion*.
2. Returns the calculated factorial.
3. Calls the function with a sample number and prints the output.

💻 *Sample Code*

python
# Function to calculate factorial
def factorial(n):
    # Base case
    if n == 0 or n == 1:
        return 1
    else:
        # Recursive case
        return n * factorial(n - 1)

# Sample number
num = 5
result = factorial(num)

# Print result
print(f"The factorial of {num} is: {result}")


✅ *Expected Output*

The factorial of 5 is: 120


 ⚙ *Task 2: Using the Math Module for Calculations*
🧩 *Problem Statement*

Write a Python program that:

1. Asks the user for a number as input.
2. Uses the *math module* to calculate and display the following:

   * Square root of the number
   * Factorial of the number
   * The number raised to the power of 2

💻 *Sample Code*

python
import math

# Ask user for a number
num = int(input("Enter a number: "))

# Perform calculations using math module
square_root = math.sqrt(num)
factorial = math.factorial(num)
power = math.pow(num, 2)

# Display results
print(f"Square root of {num} is: {square_root}")
print(f"Factorial of {num} is: {factorial}")
print(f"{num} raised to the power 2 is: {power}")

 ✅ *Example Output*

Enter a number: 5
Square root of 5 is: 2.23606797749979
Factorial of 5 is: 120
5 raised to the power 2 is: 25.0

 🧠 *Concepts Covered*

* Function definition and recursion
* Loops and conditionals
* Using Python’s built-in math module
* Input handling and formatted output
* Basic arithmetic operations

💡 *Learning Outcome*

After completing these tasks, you will be able to:

* Write and call Python functions effectively.
* Understand recursion and iteration.
* Use the math module to simplify complex calculations.
* Structure clean and readable Python scripts.

