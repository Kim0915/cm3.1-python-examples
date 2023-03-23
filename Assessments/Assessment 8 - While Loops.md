# Assessment 8: While Loops

## Section 1
write the number of times that "coding" is printed

1.
~~~python
x = 10
while x > 0:
    x += 1
    print("coding")
~~~
_____

2.
~~~python
y = 7
while y < 10:
    print("coding")
    y += 1
~~~
_____

3.
~~~python
playing = True
while playing:
    print("coding")
~~~
_____

4.
~~~python
playing = True
time = 0
while playing:
    time += 1
    if time >= 10:
        playing = False
    print("coding")
~~~
_____

5.
~~~python
swimming = True
oxygen = 100
while swimming:
    oxygen -= 3
    print("coding")
    if oxygen <= 0:
        swimming = False
~~~
_____

6.
~~~python
num1 = 2
num2 = 3

while (num1 + num2) < 10:
    print("coding")
    num2 = num1
    num1 += 1
~~~
_____

7.
~~~python
x = True
while x:
    if not x:
        print("coding")
    else:
        x = False
~~~
_____

8.
~~~python
x = 0
while x < 1:
    if x != 0:
        print("coding")
    else:
        x += 1
~~~
_____

9.
~~~python
y = 10
while x == 10:
    print("coding")
    x -= 1
~~~
_____

10.
~~~python
flying = True
has_wings = True
points = 0

while flying:
    if has_wings:
        points += 1
    else:
        flying = False
    if points >= 20:
        points += 1
        has_wings = False
for i in range(points):
    print("coding")
~~~
______

<br/>


## Section 2
Use a while loop to achieve the following results:

1.
~~~console
1
2
3
4
5
~~~
_____
_____
_____
_____
_____

2.
~~~console
110
99
88
77
66
55
~~~
_____
_____
_____
_____
_____

3.
~~~console
3
6
9
12
15
~~~
_____
_____
_____
_____
_____


<br/>


## Section 3
Use the `input()` function and a while loop to solve the following problems.

1. Polly wants to create a problem that asks the user for a password. If the password is "PollyPockets", then the program will end. Otherwise, it will ask the user for the password until they get it correct.

_____
_____
_____
_____
_____
_____
_____


2. John wants to create a computer program that asks the user to guess his favorite color. If they guess correctly (Blue), then the program stops and prints "Correct!". If the user guesses incorrectly, the program prints "Try Again" and asks to guess again.

_____
_____
_____
_____
_____
_____
_____



3. Jack has a racecar that starts each race with 100 units of fuel. Every time he completes one lap, he loses 1, 10, or 20 units of fuel randomly. Create a program that will simulate Jack's racecar and tell him how many full laps were completed in that simulation.

_____
_____
_____
_____
_____
_____
_____

## Section 3
Convert the following for loops into while loops (They should have the same output)

1.
~~~python
for i in range(10):
    print(i)
~~~
_____
_____
_____
_____
_____

2.
~~~python
for i in range(1, 20, 2):
    print(i)
~~~
_____
_____
_____
_____
_____

3.
~~~python
for i in range(2, 7):
    print(i)
~~~
_____
_____
_____
_____
_____

4.
~~~python
for i in range(10, 100, 10):
    print(i)
~~~
_____
_____
_____
_____
_____

5.
~~~python
for i in range(20):
    if i < 10:
        print(i)
~~~
_____
_____
_____
_____
_____



  
