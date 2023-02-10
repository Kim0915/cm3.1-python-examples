# Question Formats
This document will list the different question formats that are acceptable for question creation.

## Format 1: Fill in the Blank
Fairly self-explanatory. These questions will involve filling in the blank with given code.

*Example:*
~~~python
x = "Hello"
y = "World"
print(____, ____)
~~~

Fill in the blank to print "Hello World"

## Format 2: Word Bank
These questions can contain sentences or code in which students use a word bank to fill in.

*Example:*
|Word Bank   |
| ---------- |
| Dictionary |
| List       |
| Variable   |

Fill in the blanks:
1. A _____ uses keys and values
2. A _____ is ordered and contains indices.
3. `"number"` is a string. `number` is an example of a ______

or

| Word Bank|
| -------- |
| for      |
| while    |
| if       |

~~~python
_____ i in range(5):
  print(i)
~~~
Fill in the blank to print 0-4.

## Format 3: Connect the answer
These question types are similar to word bank, but will have several codes/results to connect.

*Example:*

Match the code to the result:

|     Possible Results     |
|--------------------------|
|`7`  `"Hello"`  `"World"` |


Code:
1.
~~~python
result = "Hello"
for i in range(10):
	if i == 7:
		print(result)
	else:
		result = "World"
~~~

Result: ____

2.
~~~python
x = 6
result = "Hello"
while x > 2:
	if result == "Hello":
		result = "World
	elif result == "World":
		result = "Hello"
	
	x -= 1
~~~

Result: ____

3.
~~~python
result = "World"

while result == "Hello":
	print(result)

print(7)
~~~

Result: ____


## Format 4: Write the Result
These questions should have some type of code that produces some type of output (whether it be output of a function or printing something to the console). The student's duty is to predict the output of the code.

*Example:*
~~~python
x = "Hello"
y = "World"
z = "!"

print(x, y, z)
~~~
What will be printed out to the console?


## Format 5: Write the Code / Fulfill a Purpose
These questions should give the student some goal or task. The student must write their code from scratch to complete the task. The question should be simpler to execute then any of the other question formats, because they will write it from scratch.

*Example:*
~~~python

_________________________

_________________________

_________________________
~~~
Write a function to add two numbers together.
