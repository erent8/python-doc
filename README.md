## Table of Contents
 
- [Hello, World!](#hello-world)
- [Variables and Types](#variables-and-types)
- [Lists](#lists)
- [Basic Operators](#basic-operators)
- [String Formatting](#string-formatting)
- [Basic String Operations](#basic-string-operations)
- [Conditions](#conditions)
- [Loops](#loops)
- [Functions](#functions)
- [Classes and Objects](#classes-and-objects)
- [Dictionaries](#dictionaries)
- [Modules and Packages](#modules-and-packages)

## Hello, World!

The "Hello, World!" program is a simple program that outputs "Hello, World!" to the screen. It is often used as a first step in learning a new programming language.

```
print("Hello, World!"),
```
Variables and Types
Variables are used to store information to be referenced and manipulated in a program.  supports different types of variables including integers, floats, and strings.


```
myint = 7
myfloat = 7.0
mystring = "hello"
```
### Lists
Lists are collections of items in a particular order. Lists can contain items of different types.


```
mylist = [1, 2, 3]
mylist.append(4)
print(mylist)  # Output: [1, 2, 3, 4]
```
### Basic Operators
Operators are used to perform operations on variables and values.  supports arithmetic, comparison, logical, and bitwise operators.


```
x = 1 + 2 * 3 / 4.0
print(x)  # Output: 2.5
```
### String Formatting
String formatting allows you to construct strings dynamically by inserting values into placeholders within a string.


```
name = "John"
print("Hello, %s!" % name)  # Output: Hello, John!
```
### Basic String Operations
 provides various string operations such as concatenation, slicing, and finding the length of a string.


```
s = "Hello"
print(s + " World")  # Output: Hello World
print(s[1])  # Output: e
print(len(s))  # Output: 5
```
### Conditions
Conditions allow you to execute code only if a certain condition is met using if, elif, and else statements.


```
x = 10
if x < 0:
    print("Negative")
elif x == 0:
    print("Zero")
else:
    print("Positive")  # Output: Positive
```
### Loops
Loops are used to iterate over a sequence (such as a list, tuple, string) or perform an action repeatedly.


```
for i in range(5):
    print(i)  # Output: 0 1 2 3 4

i = 0
while i < 5:
    print(i)  # Output: 0 1 2 3 4
    i += 1
```
### Functions
Functions are blocks of reusable code that perform a specific task. They can accept arguments and return values.


```
def add(a, b):
    return a + b

print(add(2, 3))  # Output: 5
```
### Classes and Objects
 is an object-oriented programming language. You can create classes to define objects with attributes and methods.


```
class Person:
    def __init__(self, name):
        self.name = name

    def greet(self):
        print("Hello, my name is " + self.name)

p = Person("John")
p.greet()  # Output: Hello, my name is John
```
### Dictionaries
Dictionaries are collections of key-value pairs. Keys must be unique and are used to access the corresponding values.


```
mydict = {"name": "John", "age": 25}
print(mydict["name"])  # Output: John
```
### Modules and Packages
Modules are  files containing definitions and statements. Packages are a way of structuring ’s module namespace by using “dotted module names”.


```
import math
print(math.sqrt(16))  # Output: 4.0
```
