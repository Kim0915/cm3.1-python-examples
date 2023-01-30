# cm3.1-python-examples
# Python Practice Questions Examples

## Goals
Easy problems that slowly build up in difficulty. Meant to be practiced in repetition. Ideally 10+ problems of each example type to really ingrain the concepts into the students.

## Variables

### Example 1

~~~python
x = 7

print(x)
~~~

What will be printed on the console?

### Example 2

~~~python
x = 4
y = 2
z = 3

print(x + y)
~~~

What will be printed on the console?

### Example 3

~~~python
x = ?

print(x + 1)
~~~

What number can we place in the `?` to get `5` printed to the console

### Example 4

~~~python
y = 6

print(y + z)
~~~

Complete the code to print `10` to the console

## Data Types

### Example 1
~~~python
print(type(3))
~~~

What will be printed to the console?

### Example 2
~~~python
print("1" + ?)
~~~

What can we replace `?` with to print out `"11"`

### Example 3

~~~python
print(int("2") + 3)
~~~

What is the printed to the console?

### Example 4
Fill in the blanks using the Word Bank below:

|Word Bank                           |
|------------------------------------|
| `String`   `Integer`   `Data Type` |
| `type()`   `"Hello"`   `3.0`       |


1) "Number 5" is an example of a ____.
2) ____ is an example of a string.
3) ____ is not an integer, but a float.
4) In order to see the variable's ____, we must use the function ____.
5) 16 is an ____.


## Booleans and Conditional Statements

### Example 1
Answer the following with True or False:
1) 5 is equal to 5
2) 3 is larger than 4
3) 3 is less than 7
4) 5 is greater than 5
5) 5 is greater or equal to 5
6) 4 is equal to "4"
7) False is equal to False

### Example 2
Fill in the `?` so that the answer is `True`
1) 5 == ?
2) 3 > ?
3) 1 + 1 == ?
4) 4 > 3 + ?

Fill in the `?` so that the answer is `False`
1) ? == 1
2) ? > 3
3) ? <= 2
4) 3 != 3 + ?

### Example 3
What will the following code print out?:
~~~python
if 3 == 3:
	print("Hello World")
else:
	print("Goodbye World")
~~~

### Example 4

Fill in the blank to complete the code and print out `"Success!"`
~~~python
x = ___
if x > 4:
	print("Success!")
else:
	print("Failed!")
~~~

## Loops

### Example 1
The following code prints out numbers 0-5:
~~~python
for i in range(6):
	print(i)
~~~

What can we write in the blank to print out numbers 0-10?:
~~~python
for i in range(____):
	print(i)
~~~

### Example 2
Fill in the blanks to print out:
~~~console
0
1
2
3
4
~~~

~~~python
for i in range(5):
	print(____)
~~~

### Example 3
Fill in the blank with either `for` or `while`
a)
~~~python

____ i in range(6):
	print(i)
~~~

b)
~~~python

____ c in "Hello":
	print(c)
~~~

c)
~~~python
x = 5
____ x > 3:
	print(x)
	x -= 1
~~~

### Example 4
Match the code to the result:

|     Possible Results     |
|--------------------------|
|`7`  `"Hello"`  `"World"` |


Code:
a)
~~~python
result = "Hello"
for i in range(10):
	if i == 7:
		print(result)
	else:
		result = "World"
~~~

Result: ____

b)
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

c)
~~~python
result = "World"

while result == "Hello":
	print(result)

print(7)
~~~

Result: ____

