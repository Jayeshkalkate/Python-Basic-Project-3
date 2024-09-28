# Python-Basic-Project-3

# Create a factorial program :-

# The factorial formula is :- n! = n x (n -1)!

# Program 1 :-

# First we get a number from the users to find a factorial of that number .

factorial_number = (int(input("Enter the number to find factorial : ")))

start = 1

for number in range(1,factorial_number + 1) :
    start *= number

print(f"The factorial of an number {factorial_number} is : {start}")

# Shortcut Program :-

# By using the import math it's the simple way of calculate factorial .

# import math

# Under the def function factorial and add a number to find factorial_class of number .

# def factorial_class(n):

# By using the return function instant call the function def factorial

#    return math.factorial(n)

# num = 10

# print(factorial_class(num))
