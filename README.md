# firstpythonprogram
# My First Python Program - A Calculator

def my_calculator(a, b):
    a = input("Please enter first number: ")
    b = input("Please enter second number: ")
    c = input("Please enter the operation (+, -, *, /): ")
    if c == "+":
        print(f"The result is: {float(a) + float(b)}")
    elif c == "-":
        print(f"The result is: {float(a) - float(b)}")
    elif c == "*":
        print(f"The result is: {float(a) * float(b)}")
    elif c == "/":
        if b == "0":
            print("Error: Division by zero is not allowed.")
        else:
            print(f"The result is: {float(a) / float(b)}")


print("Welcome to the simple calculator!")
a = 0
b = 0

my_calculator(a, b)
