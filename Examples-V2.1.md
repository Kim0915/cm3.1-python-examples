# Python Exercises V2.1 (1 of 4)

## Topic: Data Types
A data type is a way of describing what kind of information is stored in a computer or in a program. It's like different kinds of containers that hold different types of things. Just like how you might have a pencil case for your pencils, and a lunchbox for your lunch, a computer has different kinds of containers for different kinds of information.

For example, some of the most common data types are numbers (like 1, 2, 3), words (like "cat" or "dog"), and dates (like "February 17th, 2023"). Each of these different types of information is stored in a different kind of container so that the computer knows how to handle it and use it in the right way.

So, just like how you might use different containers for your different things, a computer uses different data types to store and organize different kinds of information

## Strings and Integers
These questions will cover two types of data types in particular: `Strings` and `Integers`

A string is a type of data that represents text or words. It's like a line of letters or words, just like the words you might see in a book or on a sign. For example, "cat" and "dog" are both strings.

An integer, on the other hand, is a type of data that represents whole numbers. It's like a number that you count with, like how you might count how many fingers you have (1, 2, 3, 4, 5). For example, 1, 2, and 3 are all integers.

So the main difference between a string and an integer is that a string represents text or words, while an integer represents whole numbers. They're both types of data, but they're used for different things.

## Example Problem 1:
What will be printed out to the console, and why?
~~~python
print("3" + "3")
~~~

Answer: "33"
#### Explanation
"3" is a string. When you add/subtract integers together, they are treated like normal whole numbers in math. However, when you add strings, they `concatenate`. This means that it will be added to the end of the other string. 

For example:
~~~python
print("Hello" + "World")
~~~
will print
~~~console
HelloWorld
~~~

Similarly, "3" + "3" will print "33", wheras 3 + 3 will print 6.


## Example Problem 2
What will be printed out to the console, and why?
~~~python
print(str(5) + 5)
~~~

Answer: we will get an error
#### Explanation
You cannot add/subtract different data types in Python. Because str(5) = "5", you cannot add it to the `integer` 5. Thus, our code will result in an error. When you are adding things together, make sure you pay attention to the data types that you are adding.

#### Bonus
Can you think of way to make the above code print "55" using conversion functions (i.e. str() int() )? How about 10?

###### Explanation 1
~~~python
print(str(5) + str(5))
~~~
To make it print "55", we switch the second `integer` to be a `string` so that the `+` "concatenates" instead of "adding"

###### Explanation 2
~~~python
print(int(5) + 5)
~~~
To make it print 10, we switch the first conversion function `str()` to be `int()` so that the first 5 is an `integer`. The second 5 is already an integer. We know this because there are no quotation marks around the number. Since there are 2 integers, the `+` "adds" instead of "concatenating".

<div style="page-break-after: always;"></div>
 

## Data Types Practice Problems

#### Problem 1
Decide whether the following results are a `string`  or an `integer`:
1) "Hello" ____________
2) 55  ____________
3) 55 + 5  ____________
4) "55" + "5"____________
5) "55" + str(5) ____________
6) int("10") ____________
7) 10 ____________
8) "10" + str(10) ____________
9) "Two" ____________
10) "3" ____________

#### Problem 2
Write the outcome of the following code. Then, say whether the output is a `integer` or a `string`:



~~~python
x = 5
print(x + 2)
~~~
1) __________________ 

~~~python
x = 6
print(str(6))
~~~
2) __________________ 

~~~python
v = 5
print(str(5+5))
~~~
3) __________________ 


~~~python
z = "10"
print(z + "1")
~~~
4) __________________ 


~~~python
v = str(7)
print(v + str(3))
~~~
5) __________________ 


#### Problem 3
Fill in the blank so that the code prints out a `string`
~~~python
x = ____(2222)

print(x)
~~~

#### Problem 4
Fill in the blank so that the code prints out a `integer`
~~~python
x = ___("55") + 10
print(x)
~~~

#### Problem 5
Fill in the blank to print the correct outcome:
1) "55"
~~~python
x = "5"
print(x + ____)
~~~


2) "Hello 10"
~~~python
x = "Hello"
print(x + ____)
~~~


3) 550
~~~python
x = "55"
y = "0"
print(____(x+y))
~~~


4) "55"
~~~python
x = "5"
print (x + ___(5))
~~~

#### Problem 6
Use conversion functions (`int()` and `string()`) to print the `integer` 10. Rewrite the code in the lines provided.

1)
~~~python
x = "10"
print(x)
~~~

______________

______________

______________

2)
~~~python
x = "5"
y = "5"
print(x + y)
~~~

______________

______________

______________
3)
~~~python
x = 5
y = "5"
print(x + y)
~~~

______________

______________

______________


4)
~~~python
x = "Hello"
y = "World"
z = 10
print(z)
~~~
______________

______________

______________

#### Problem 7
In your own words, what is the difference between a `string` and an `integer`?

<div style="page-break-after: always;"></div>


# Python Exercises V2.1 (2 of 4)

## Topic: Boolean Values
In the last exercise, we practiced identifying different `data types`. A boolean value is another `data type` that can be either true or false. It's like a switch that can be turned on or off. For example, when you ask "Is it raining outside?", the answer can be either "Yes, it's raining" (True) or "No, it's not raining" (False). In programming, we use boolean values to make decisions. For instance, if it's raining, you might want to take an umbrella, but if it's not, you might not need one. So we can use a boolean value to decide whether or not to take an umbrella.

In programming we use something called `comparison operators` to determine whether a statement is True or False. You may have seen some `comparison operators` in your math classes. For example: 2 > 4 is False and 3 > 2 is True.

However, there are some other operators that are similar but not exactly the same as the ones you've seen in school. Here is a list of all the `comparison operators':
- < : less than
- \> : greater than
- <= : less than or equal to
- \>= : greater than or equal to
- == : equal to
- != : not equal to

Remember, any time you see these symbols, the result is going to be either `True` or `False`.

### Example 1
What is the result of the following code?:
~~~python
x = 7
print(x > 7)
~~~
Answer: False

#### Explanation
x = 7. Seven is not greater than 7, so the console prints `False`. If we printed (x >= 7), it would be True.

#### Example 2
How can we make this statement `True`?
~~~python
x = 5
print(x != 5)
~~~

Answer: We can change x to not be 5, or we can change the 5 in the print statement to not be 5.

#### Explanation
Since the `comparison operator` is `not equals to`, we need to make sure that the two values that are being compared are not the same.

<div style="page-break-after: always;"></div>


## Boolean Values Practice Problems

#### Problem 1
Write whether the following statements are `True` or `False`
1) 5 == 5
2) 5 != 4
3) 3 > 2
4) 2 == 3
5) 2 == 1+1
6) 3 < 3
7) 4 <= 4
8) 4 <= 5
9) 100000 <= 1
10) 2 + 2 == 1 + 3

#### Problem 2
Fill in the blank to make the following statements be `True`
1) 3 == _____
2) 3 > _____
3) 3 <= _____
4) 5 != ______
5) 10 == ______
6) 10 + _____ == 15
7) 3 + 1 > _____
8) 1000000000000000000000000000000000000000 <= ______
9) 11 == 11 + ____
10) 12 < 1 + ____

#### Problem 3
Fill in the blank to make the following statements be `False`
1) 3 == _____
2) 3 > _____
3) 3 <= _____
4) 5 != ______
5) 10 == ______
6) 10 + _____ == 15
7) 3 + 1 > _____
8) 1000000000000000000000000000000000000000 <= ______
9) 11 == 11 + ____
10) 12 < 1 + ____


<div style="page-break-after: always;"></div>


# Python Exercises V2.1 (3 of 4)

## Topic: Conditional Statements
Conditional statements are like instructions for a computer to follow based on certain conditions. It's like giving the computer a question and telling it what to do if the answer is "yes" and what to do if the answer is "no."

For example, let's say you want to make a program that tells you if it's time to go to bed. You might ask the computer, "Is it past my bedtime?" If the answer is "yes," then the computer will tell you to go to bed. But if the answer is "no," then the computer will tell you that it's not time for bed yet.

So conditional statements are a way to make your program do different things depending on the answer to a question. They help the computer make decisions and do the right thing based on the situation.

## if 
We can write conditional statements in Python using the keywords `if`, `elif` and `else`. 

### Example 1
What will the following code print out?
~~~python
x = 2 + 2
if x < 3:
	print("Nice!")
elif x > 4:
	print("Great!")
else:
	print("Cool!")

~~~

Answer: "Cool!"

#### Explanation
x = 2 + 2, thus x = 4. (4 < 3) is `False` so we skip the next indented line.
(4 > 4) is also `False` since 4 is not greater than 4. Finally, we arrive at `else`, so we print "Cool!"

### Example 2
What will the following code print?
~~~python
x = 10
if x > 5:
	print("Hello")
elif x > 6:
	print("World!")
else:
	print("Bye!")

if x > 7:
	print("Friend!")
else:
	print("Enemy!")
~~~

Answer:
~~~console
Hello
Friend
~~~

#### Exaplanation
x = 10. (x>5) is `True` so we print "Hello". The first if statement was true, so we ignore any `elif` or `else` that are under this if statement. However, we must still check for any new `if` statements. (x > 7) is `True`, so we print "Friend!". We do not print "Enemy!", because the `else` is part of the previous `if` statement.

## Conditional Statements Practice Problems

#### Problem 1
Write what will be printed to the console:
1)
~~~python
x = 5

if x == 5:
	print("Hello")
else:
	print("Bye Bye!")
~~~

2) 
~~~python
x = 5

if x != 5:
	print("Hello")
else:
	print("Bye Bye!")
~~~

3)
~~~python
x = 5

if x + 2 <= 7:
	print("Hello")
else:
	print("Bye Bye!")
~~~

4)
~~~python
x = "Woah"

if x == "Woah":
	print("Hello")
else:
	print("Bye Bye!")
~~~

5)
~~~python
x = 5 + 5

if x <= 5:
	print("Hello")
else:
	print("Bye Bye!")
~~~

#### Problem 2
Fill in the blank so that `True` gets printed to the console
1)
~~~python
x = 2
y = 10

if x + y == ____:
	print(True)
else:
	print(False)
~~~

2)
~~~python
x = 12
y = 21

if x ___ y:
	print(True)
else:
	print(False)
~~~

3) 
~~~python
x = 10
y = 100

if ___ >= ___:
	print(False)
else:
	print(True)
~~~

#### Problem 3
Fill in the blank so that `False` gets printed to the console
1)
~~~python
x = 2
y = 10

if x + y == ____:
	print(True)
else:
	print(False)
~~~

2)
~~~python
x = 12
y = 21

if x ___ y:
	print(True)
else:
	print(False)
~~~

3) 
~~~python
x = 1000
y = 200

if ___ >= ___:
	print(False)
else:
	print(True)
~~~

#### Problem 4
what will be printed to the console?: 
1) 
~~~python
playing = True
if playing:
	print("You are Playing")
else:
	print("You are not Playing")
~~~

2)
~~~python
running = False
if running:
	print("Go go go!")
else:
	print("Start Running!")
~~~

3)
~~~python
running = True
if running:
	print("Hello!")
if running:
	print("World!")
~~~

4)
~~~python
running = True
if running:
	running = False
	print("Hello!")
if running:
	print("World!")
~~~

#### Problem 5
Match the result to the code:
|  | Word Bank | |
| - | - | - |
| "Hello World" | "Goodbye World" |15|
| 25 |10|True|


1)
~~~python
x = "Hello"
y = "World"
if x == y:
	print(15)
elif x != y:
	print(10)
else:
	print(True)
~~~

2)
~~~python
x = 15
if x < 20:
	print(x)
else:
	print("Goodbye World")
~~~

3)
~~~python
x = "Hello"
y = "World"
z = 25
x = 15
if z < x:
	print(True)
elif x < z:
	print(x, y)
else:
	print(False)
~~~

4)
~~~python
x = 10
if x == 10:
	print(True)
else:
	print(False)
~~~

5)
~~~python
x = "Hello"
y = "World"
if x != y:
	print("Goodbye World")
elif 5 == 5:
	print("Hello World")
else:
	print(True)
~~~

6)
~~~python
x = 5
y = 5

if x == y:
	print(x * y)
else:
	print(True)
~~~

<div style="page-break-after: always;"></div>


# Python Exercises V2.1 (4 of 4)

## Topic: Boolean Operators
In the previous pages, we covered `boolean values` and `conditional statements`. `Boolean Operators` are special words that help us combine or compare boolean values (True/False). There are three main boolean operators: `and`, `or`, and `not`.

The word `and` is like saying "both things have to be true." For example, if you want to go to the park `and` play on the swings, both things have to be true. If the swings are broken, you can't go to the park.

The word `or` is like saying "either one thing or the other thing can be true." For example, if you want to have a snack, you might ask for an apple or a banana. You don't need both, just one of them.

The word `not` is like saying "the opposite of what you think." For example, if you think it's sunny outside, "not sunny" means it's not sunny outside (it's cloudy, rainy, or nighttime).

So boolean operators are like special words that help us combine or compare true/false statements to make decisions in programming.

Boolean Operators:
- `and` : both values need to be True.
- `or` : One or both values need to be True.
- `not` : Opposite of whatever the value is.

### Example 1
Write the correct `Boolean Operator` to make the console print `True`
~~~python
x = 7
y = 5
if x < 10 ___ y > 10:
	print(True)
else:
	print(False)
~~~

Answer: or

#### Explanation
x = 7, which is less than 10. However, y=5 which is not greater than 10. So only one of the conditions is True. If we want the statement to be `True`, we use `or`.

### Example 2
What will the following code print out?:
~~~python
won = True
if won:
	won = False
	print("You won!")
if not won:
	print("You Lost!")
~~~

Answer:
~~~console
You won!
You Lost!
~~~

#### Explanation
won is set to True. So the first conditional statement gets activated and sets won to `False`, then prints "You won!".
Then, the second conditional statement also gets activated since `not False` is `True`. Thus, we also print "You Lost!"

### Example 3
What will be printed to the console?
~~~python

if (True and True) or (True and False):
	print(True)
else:
	print(False)
~~~

Answer: `True`

#### Explanation
(True and True) is True, since both are True. (True and False) is False, since both need to be True. Finally, (True) or (False) is True, since only one needs to be True. Thus, the answer is True.

<div style="page-break-after: always;"></div>


## Boolean Operator Practice Problems

#### Problem 1
Determine whether the following statements are `True` or `False`

1) True and False
2) True and True
3) False and False
4) True or False
5) False or True
6) False or False
7) not True or not False
8) not True and False
9) not True or True
10) not False and True
11) not True and not True

#### Problem 2
Determine whether the following statements are `True` or `False`
1) (2 == 2) or (3 != 3)
2) (2 == 2) and (3!= 3)
3) (5 > 4) or (3 < 2)
4) not(5 < 3)
5) not(5 == 5) or False
6) not(3 == 2) and not(False)
7) (2 > 2) or (2 >= 2)
8) (3 == 5) and (3 == 3)
9) (3 != 4) and not(3 == 3)
10) (7+2 > 9) or (8+2 == 11)

#### Problem 3
Complete the code:
|   | Word Bank|   |
| - | -------- | - |
| `and` | `not` | `or` |
| `>`   | `<`   | `==` |

1)
~~~python
if True ____ False:
	print("Complete!")
~~~

2) 
~~~python
if True _____ True:
	print("Complete")

~~~

3)
~~~python
if 5 ____ 3 or False:
	print("Complete")
~~~

4)
~~~python
False or _____ False:
	print("Complete")
~~~

5)
~~~python
if not(3 ____ 3) and True:
	print("Complete")
~~~

6)
~~~python
if (True and True) and (3 ____ 3):
	print("Complete")
~~~

#### Problem 3
Fill in the blanks so that the code prints `True`
1)
~~~python
running = False
if ____ running:
	print(True)
else:
	print(running)
~~~

2)
~~~python
x = 5 * 3

if x > 20 ____ x < 17:
	print(True)
else:
	print(False)
~~~

3)
~~~python
y = "Playing"
z = ____

if (y == "Playing") and z:
	print(False)
else:
	print(True)
~~~

4)
~~~python
if (True or False) and not(False ___ False):
	print(True)
else:
	print(False)
~~~


#### Problem 4
Fill in the blanks to the code so that it prints `True` to the console:
~~~python
x = 3
y = 0
if True ___ False:
	x = 5

if x == 5 and not(____):
	y = 7

if y > 5:
	z = not(____)

if x ___ y:
	print(z)

~~~


#### Problem 5
Fill in the blanks to the code so that it prints `False` to the console:
~~~python
x = "Lion"
z = True
y = False

if x ____ "Tiger":
	print(x ___ y)
~~~


<div style="page-break-after: always;"></div>


