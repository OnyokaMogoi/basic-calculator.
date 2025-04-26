# Basic Calculator Program

# Ask the user for two numbers
num1 = float(input("Enter the first number (example: 50): "))
num2 = float(input("Enter the second number (example: 20): "))

# Ask the user for the operation
operation = input("Enter the operation (+, -, *, /) (example: +): ")

# Perform the calculation based on the operation
if operation == '+':
    result = num1 + num2
    print(f"{num1} + {num2} = {result}")
elif operation == '-':
    result = num1 - num2
    print(f"{num1} - {num2} = {result}")
elif operation == '*':
    result = num1 * num2
    print(f"{num1} * {num2} = {result}")
elif operation == '/':
    if num2 != 0:
        result = num1 / num2
        print(f"{num1} / {num2} = {result}")
    else:
        print("Error: Cannot divide by zero.")
else:
    print("Invalid operation!")
