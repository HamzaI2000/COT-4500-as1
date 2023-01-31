# COT-4500-as1
COT4500 Assignment 1



import math 

binary = "010000000111111010111001" 
#This is the binary number used for the program 

#convert this binary number to decimal 
decimal = int(binary,2)
print("{:.5f}".format(decimal))
print("\n")

#This is for three digit chopping
print('%.3f'% decimal)
print("\n")

#Repeat
print(round(decimal,3))
print("\n")

#This is used to establish how absolute and relative error is calculated
x = math.pi
xbar = decimal
error = x-xbar
abs_error = abs(x-xbar)
rel_error = abs_error/xbar

print('Error:', error)
print('Absolute Error:', abs_error)
print('Relative Error:', rel_error)
