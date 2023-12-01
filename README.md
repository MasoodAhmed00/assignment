# ***Assignment of Exploratory Data Analysis***
##
# Content
[1. Variable in Python](#1-variables-in-python)\
[2. Python as Calculator](#2-python-as-calculator)\
[3. Function in Python](#3-function-in-python)\
[4. Strings in Python](#4-strings-in-python)\
[5. Lists in Python](#5-lists-in-python)\
[6. Tuples in Python](#6-tuples-in-python)\
[7. Dictionaries in Python](#7-dictionaries-in-python)\
[8. Conditions in Python](#8-conditions-in-python)\
[9. Loops in Python](#9-loops-in-python)\
[10. Linear Regression](#10-linear-regression-using-scipy-libraray)
# 1. Variables in python

```python
# how to create variable in python(24 is my roll number)
x = [1,2,3,4,5,6,7,8,9,24]

y = [10,20,30,24,53,60,75,80,95,10]
```
```python
# To check the result we use print command
print(x)
print(y)
```
##
# 2. Python as calculator

```python
# Minus command
a = 22 - 10
```
```python
# For Multiplication we use(*)
ab = 22*2
ab
```
```python
# for Division we use (/)
abc = 22/2
abc
```
```python
# Here we use both sign (/) & (*)
abd = 22/3*4
abd
```
##
# 3. Function in Python
> To create function in python we use **def**

```python
# Here we define a simple Function that will add two given numbers
def add_num(a,b):
    sum = a+b;
    return sum;
```    
```python
# To check our function
add_num(22,28)
```
```python
#complex  function 
def my_function (a,b,c):
    sum = a+b-c;
    return sum;
num1= int(input("plz enter number"))
num2= int(input("enter 2nd_number"))
num3= int(input("enter 3rd_number"))
print("Thats is result cheeers!",my_function(num1,num2,num3))
```
# 4. Strings in Python
```python
# we create string by putting quotes around test
ma = "Masood Ahmed is a good guy"
print(ma)
```
## Multiline string 
```python
# for multiline string we use 3(')
id ='''My name is Masood Ahmed . My roll number is 24 iam studying in department of statistics in third year'''
```
# 5. Lists in Python
```python
# we can create list by using brackets or by built-in function
my_list = [2,4,2,4,2,4,24]
mylist 
```
```python
my_list2 = ["a","b","c","d"]
my_list2
```
# 6. Tuples in Python
> We create Tuple by the help of (parentheses)
```python
my_tuple(2,4,2,4,2,4,24)
my_tuple
```

# 7. Dictionaries in Python
> Dictionary is an unorderd set of key and values. We create dictionary by the help builtin function and {}
```python
# Simple dictionary
my_dict{"pencil":10,"copy":20,"marker":30}
my_dict
```
# 8. Conditions in Python
## Condition IF & ELSE
```python 
# If codition
test_score= 100
if test_score > 60:
    print("Congratulaions! you are pass")
```
```python
#IF & ELSE condition
if test_score > 60:
    print("Congratulaions! you are pass")
else:
    print("Shhh,you fail.")
```
# 9. Loops in Python
> In python there are two types of loops FOR lopp & WHILE loop

```python
# It will print Salam five times
for x in range(0,5):
    print("Salam")
```
```python
my_list3 = [1,2,3,4,5,6,7,8,9,10]
for num in my list:
    if num==8
    print("Item found Succsesfully")
```
# 10. Linear Regression using Scipy libraray
```python
# import required libraries
import numpy as np
from scipy.stats import linregress
import matplotlib.pyplot as plt
```
```python
# Load the data x and y 
x = [10,20,30,40,50]
y = [20,40,50,40,50]
```
```python
# Fit the linear regression model
slope,intercept,r_value,p_value,std_err=stats.linregress(x, y)
```
```python
# To print the results
print("Slope:", slope)
print("Intercept:", intercept)
print("R-squared:", r_value)
print("Standard error:", std_err)
```
```python
# To predict future values
predicted_y=slope * 6.0 + intercept
```

>To create a simple scater plot of by using upper variables

```python
fig1 = plt.scatter(x,y,c='yellow')
fig1      #To show fig
```
