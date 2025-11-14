#TASK 1

def factorial(n):
    fact = 1
    for i in range(1, n + 1):
        fact *= i
    return fact

num = 5
print(f"The factorial of {num} is: {factorial(num)}")


#TASK 2

import math

# Ask the user for a number
num = int(input("Enter a number: "))

# Calculate using math module
square_root = math.sqrt(num)
factorial = math.factorial(num)
power = math.pow(num, 2)   # num squared

# Display results
print(f"Square root of {num} is: {square_root}")
print(f"Factorial of {num} is: {factorial}")
print(f"{num} raised to the power 2 is: {power}")
