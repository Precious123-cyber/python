# Basic calcultion program

#Ask the user for two numbers and an operation
num1 = float(input("Enter the first numbe:"))
num2 = float(input("Enter the second number:"))
operation = input("Enter the operation (+, -, /):")

# Perform the operation baseed on user input
if operation == '+':
    result = num1 + num2
    print(f"{num1} + {num2} = {result}")
elif operation == '-':
    result = num1 - num2
print(f"{num1} - {num2} = {result}")
elif operation == '/':
if num2 != 0:
    result = num1 / num2 
    print(f"{num1} / {num2} = {result}")
else:
    print("Error: Cannot divide by zero.")
else:
print("Invalid operation. please enter +, -, or /.")
