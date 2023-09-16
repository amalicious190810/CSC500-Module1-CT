# -*- coding: utf-8 -*-
"""
Created on Sat Sep 16 16:24:38 2023

@author: pulik
"""

#%%

# Part 1: Addition and Subtraction

print("Welcome to Amal's fun addition and subtraction program!\n",  
"Please enter two numbers to continue!")

# Ask user to input two numbers
num1 = float(input('Enter your first number:\n'))
num2 = float(input('Enter your second number:\n'))

# Print and calculate addition and subtraction
print('Addition of your two numbers:',num1, '+', num2, 'is', num1+num2)
print('Subtraction of your two numbers:',num1, '-', num2, 'is', num1-num2)
print('Thanks for using our program!')

#%%

# Part 2: Multiplication and Division

print("We're pleased to announce that since the addition and subtraction\n",
"program was such a hit, we've released a premium subscription only program\n",
"for multiplication and division!\n",  
"Please enter two numbers to continue!")

# Ask user to input two numbers
while True:
    num1 = float(input('Enter your first number:\n'))
    num2 = float(input('Enter your second number (make sure this is not zero):\n'))
    
    # Check if num2 is not equal to zero to avoid error
    if num2 != 0:
        break 
    else:
        print("Division by 0 is not allowed silly, please try again.")
    
# Print and calculate multiplication and division
print('Multiplication of your two numbers:',num1, '*', num2, 'is', num1*num2)
print('Division of your two numbers:',num1, '/', num2, 'is', num1/num2)
print('Thanks for using our program!')

