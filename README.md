# Intro-to-Python-Assignment
# Basic Calculator Program 
# Create a simple Python program that asks the user to input two numbers and a mathematical operation (addition, subtraction, multiplication, or division).Perform the operation based on the user's input and print the result.Example: If a user inputs 10, 5, and +, your program should display 10 + 5 = 15.

num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))
operation = input("Enter an operation (+, -, *, /): ")

if operation == "+":
    result = num1 + num2
    print(f"{num1} + {num2} = {result}")
elif operation == "-":
    result = num1 - num2
    print(f"{num1} - {num2} = {result}")
elif operation == "*":
    result = num1 * num2
    print(f"{num1} * {num2} = {result}")
elif operation == "/":
    if num2 != 0:
        result = num1 / num2
        print(f"{num1} / {num2} = {result}")
    else:
        print("Error! Division by zero is not allowed.")
else:
    print("Invalid operation! Please enter +, -, *, or /.")
    
# Result
Enter the first number: 10
Enter the second number: 5
Enter an operation (+, -, *, /): +
10.0 + 5.0 = 15.0
