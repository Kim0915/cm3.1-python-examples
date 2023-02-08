# Practice Problem Creation Guide by Topic
This document will address the different types of exercise examples we are looking for and the guidelines that constitute the question types.
The lesson topics are each separated into a number of question types that scale gradually in difficulty. 


## Topic 1: Variables
This topic will cover basic variable concepts learned in Python 1
#### Type 1: Single Variable Values
These questions will involve questions with one variable. These questions can ask any type of question, but the amount of variables used should be limited to one. Some good question formats may be `fill in the blank`, or `guess the result`. 
*Examples:*
~~~python
x = ____
print (x)
~~~
Fill in the blank so that your name is printed in the console

#### Type 2: Two Variable Values
These questions should be basic questions that contain exactly 2 variable values
*Example:*
~~~python
x = 5
y = 6

print(x)
~~~
What will be printed?

#### Type 3: Multiple Variable Values
These questions should contain at least 3 variables and can contain some more difficult topics such as `data types` or `integer operations`
*Example:*
~~~python
x = "Hello"
y = 7
z = 6
print(x)
print(y+z)
print(z)
~~~

Write out what will be printed next to each line of code


## Topic 2: Data Types
This topic will cover data types. Students should understand what data types are, how to check an object's data type, and be able to identify different data types by sight.

#### Type 1: Simple Identification Problems
These problems should be simple data type identification problems. Some valid question formats may be `connect the answer`, `fill in the blank` , or `word bank`.
*Example:*
~~~python
print(type("Hello"))
~~~
What is printed out to the console?

#### Type 2: Type Conversions
These problems should be about converting data types
*Example:*
~~~python
print("1" + "1")
~~~
What will be printed out?

~~~python
print(int("1"))
~~~
What will be printed out

#### Type 3: Complex Data Type Conversions
These questions should be about identifying and converting data types. These problems may contain multi-layered questions that are more complex than the previous two types.
*Example:*
~~~python
x = 1
y = 5

print(str(x) + str(y))
print(str(x+y))
~~~
What will be printed as a result?


## Topic 3: Booleans & Conditional Statements
This topic will cover Boolen values and conditional statements. Students should understand boolean values and boolean operators. Additionally, students should be able to construct conditional statements and identify results using proper logic.

#### Type 1: Boolean Values
These questions should discuss Boolean Values (True and False) in Python with one or less boolean operators.
*Example*:
~~~python
print(7 == ___)
~~~
Fill in the blank to print False on the console

#### Type 2: Multiple Operators
These questions should be similar to the type 1 questions, but may contain 2 or more boolean operators.
*Example:*
~~~python
x = 6
y = 5
z = 6

print( x == z and x != y)
~~~

What will be printed to the console?

#### Type 3: Simple Conditional Statments
These questions will involve conditional statements involving conditions that contain one or less boolean operators. Conditional statements should also be limited to one if and else.
*Example*:
~~~python
x = "Hello"
y = "World"
if x == "Hello":
  print(x, y)
else:
  print("Goodbye")
~~~

What will be printed out to the console?

#### Type 4: Complex Conditional Statements
These questions can contain multiple conditional statements as well as multiple boolean operators. Still, keep in mind this is python 1 level and should still be simple to solve
*Example:*
~~~python
x = 5
y = world

if x == "World":
  print(y)
elif y == "WORLD":
  print("Hello!")
elif x > 2 and y == "world":
  print(x, y)
else:
  print("Goodbye")
~~~
What will be printed out to the console?


## Topic 4: For Loops
This topic will cover for loops. Students should be able to use for loops to iterate through ranges. We will practice how to iterate through other iterable objects in the later topics

#### Type 1: Identify a Range
These questions will involve using a for loop to iterate through a range of integers.
*Example:*
~~~python
for i in range(___):
  print(i)
~~~

Fill in the blank so that the numbers 0-10 are printed out

#### Type 2: Ranges with Intervals
These questions will involve using a for loop to iterate through a range of integers. However, these questions should also involve start/end integers for the range as well as range intervals.
*Example:*
~~~python
for n in range(1,___,___):
  print(n)
~~~
fill in the blanks to print out the numbers 1-10

#### Type 3: Nested For Loops
These questions will involve nested for loops
*Example:*
~~~python
for i in range(2):
  for j in range(3):
      print("Hello")
  print("World")
~~~

How many times will "Hello" be printed to the console. How about "World"?


## Topic 5: While Loops

#### Type 1: Complete the Loop
These questions will involve choosing/filling in the correct answer to complete the loop with desired output.
*Example*:
~~~python
x = 0

while x < 7:
  print("Hello")
  x += ___
  
~~~

Fill in the blank to print "Hello" 7 times.

#### Type 2: Condition to stop
These questions will involve while loops where students must identify the correct condition to "stop" the loop
*Example:*
~~~python
import random
running = True

while running:
  x = random.randint(10)
  if _______:
    running = False
print(x)
~~~

What can we put in the blank to print the number 5?

#### Type 3: Loop Conversion
Convert a For loop to a while loop and vice versa
*Example:*
~~~python
for i in range(5):
  print(i)
~~~
Create a while loop that will print the same output as the above for loop


## Topic 6: Functions

#### Type 1: Basic Identification
These questions should have students identifying the components of a function.
*Example*:
~~~python
def sayHello():
  print("Hello")
  return 0
~~~
What is the returned `value` of this function

or 

~~~python
def addOne(x):
  return x + 1
~~~
What is the `input` for this function?

#### Type 2: I/O
These questions should have students practicing with input and outputs of functions to get the desired result
*Example:*
~~~python
def subtractTwo(x):
  return x - 2
 
________
~~~
Fill in the blank to print out the number `5`

~~~python
def square(__):
  return z ** 2
~~~
Fill in the input to complete the function
or
~~~python
def addOne(p):
  return ______
~~~
Fill in the blank to make the function `addOne()` add 1 to the input.

#### Type 3: Fulfill a Purpose
These questions will have students creating functions to fulfill some type of purpose. The goal should be relatively simple to achieve.
*Example:*
~~~python
______________

______________

______________
~~~
Create a function to add 2 numbers together.
  
  
## Topic 7: Lists

#### Type 1: List Index
These questions should focus on identifying the index of certain values in a list.
*Example:*
~~~python
vegetables = ["Onion", "Potato", "Celery"]
~~~
What index is the string `"Onion"` in?
or
~~~python
fruits = ["Tomato", "Guava", "Pineapple"]
print(fruits[___])
~~~
Fill in the blank to print the word "Pineapple"

#### Type 2: Basic List Functions
These questions should have students identifying the result using exactly 1 list method
*Example:*
|Word Bank|
| ------- |
| append()|
| pop()   |
| add()   |
| insert()|

~~~python
fruits = ["apple", "orange", "banana"]
fruits._____("grape")
~~~
Which function can we use from the word bank to add "grape" to the end of the list.

#### Type 3: Intermediate List Functions
These questions should have students identifying results with 2 or more list functions involved
*Example:*
~~~python
veges = ["celery", "lettuce", "eggplant"]
veges.pop(-1)
veges.append("spinach")

print(veges)
~~~
What are the elements of the list `veges`?

#### Type 4: Fulfill a Purpose
These questions should challenge students to fulfill some type of task given a list.
*Example:*
~~~python
fruits = ["Mango", "Apple", "Pear"]

__________________________________

__________________________________

__________________________________
~~~
Remove the first item in the list, then add "Orange" to the end of the list.
The final result of fruits should be ["Apple", "Pear", "Orange"]


## Topic 8: String Functions

#### Type 1:
