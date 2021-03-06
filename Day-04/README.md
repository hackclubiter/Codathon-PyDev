Hey everyone!!! Yesterday we completed list, dictionaries, tuples and sets. So today lets dive deeper into Python programming language! 🚀

Today we gonna cover the methods and functions in Python.

<hr>

## Functions:
A function is a block of code to carry out a specific task, will contain its own scope and is called by name. All functions may contain zero(no) arguments or more than one arguments. On exit, a function can or can not return one or more values.

### Basic function syntax:
```python
def functionName( arg1, arg2,….):
   ……
   # Function_body
   ……
```

#### Example:
```python
def sum(num1, num2):
   return (num1 + num2)
sum(5,6)
```
>>> 11

So from above, we see the ‘return’ statement returns a value from python function.

The function allows us to implement code reusability. There are three kinds of functions −
- Built-in functions ( As the name suggests, these functions come with the Python language, for example, help() to ask for any help, max()- to get maximum value, type()- to return the type of an object and many more.)

- User-defined functions ( These are the functions that users create to help them, like the “sum” function we have created above).

- Anonymous Functions (also called lambda functions and unlike normal function which is defined using def keyword are defined using lambda keyword).

## Methods:
A method in python is somewhat similar to a function, except it is associated with object/classes. Methods in python are very similar to functions except for two major differences.
- The method is implicitly used for an object for which it is called.
- The method is accessible to data that is contained within the class.

### General Method Syntax:
```python
class ClassName:
   def method_name():
      …………..
      # Method_body
      ………………
```

#### Example:
```python
class Pet(object):
   def my_method(self):
      print("I am a Cat")
cat = Pet()
cat.my_method()
```
>>> I am a Cat


### Object Methods:
Objects can also contain methods. Methods in objects are functions that belong to the object.

#### Example:
Insert a function that prints a greeting, and execute it on the p1 object:
```python
class Person:
  def __init__(self, name, age):
    self.name = name
    self.age = age

  def myfunc(self):
    print("Hello my name is " + self.name)

p1 = Person("John", 36)
p1.myfunc()
```

>>> Hello my name is John

<hr>
So, these are the basics of Python Methods & Functions. Read more about by the following resources:

### For Functions:
1. [Python Functions](https://www.w3schools.com/python/python_functions.asp)
2. [Python Functions](https://www.programiz.com/python-programming/function)
3. [Built-in Functions](https://docs.python.org/3/library/functions.html)
4. [Video- ](https://www.youtube.com/watch?v=u-OmVr_fT4s)

### For methods:
1. [Method Objects](https://docs.python.org/3/tutorial/classes.html#method-objects)
2. [Python Method – Classes, Objects and Functions in Python](https://data-flair.training/blogs/python-method/)
3. [Python String Methods](https://www.w3schools.com/python/python_ref_string.asp)
4. [Video- ](https://www.youtube.com/watch?v=fbaSAS9DWZw)


<hr>

#### More:

1. [DEFINATIONS](https://www.programiz.com/python-programming/function)
2. TYPES 
   - [USER DEFINED](https://www.programiz.com/python-programming/user-defined-function)
   - [BULIT IN](https://www.programiz.com/python-programming/methods/built-in)
3. [ARGS AND KWARGS](https://www.programiz.com/python-programming/args-and-kwargs)
4. [Lambda function](https://www.w3schools.com/python/python_lambda.asp)
5. [Map function](https://www.geeksforgeeks.org/python-map-function/)
6. [Filter function](https://www.geeksforgeeks.org/filter-in-python/)

<hr>

### Some try out questions:

1. Volume of a sphere

> Write out your solution by hand as an equation with an input radius, then try to convert your logic to code.

2. Range check function

> Keep in mind how to use the in operator and the range() function. How can you use in to check if something is in a list?

3. Upper Case and Lower Case strings

> Whats a good way to iterate through the string? A for loop perhaps? How can you keep track of you counts? A variable or maybe even a dictionary with a key for upper and a key for lower, then add counts to the value corresponding to the correct key.

4. Unique numbers in list.

> Try using set() or even just using a for loop with a list and append numbers that you haven't already seen

5. Multiply all numbers in a list

> Use a for loop to go through the list and take advantage of *= which operate similarly to +=.

6. Palindrome check

> Remember what s[::-1] does if s is a string, or find a built-in way to reverse a string (function or method)

7. Pangram check

> This is really tricky, but try using set() and feel free to check the answer for this one!

<hr>

We are done with the 4th day of our 7 days of challenge. Hope you all are enjoying and don't forget to learn more and practice.

