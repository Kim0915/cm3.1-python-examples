# Python Assessment 9: Functions

## Section 1
Write the result of the following code:

1.
~~~python
def addOne(x):
    x += 1
    return x
print(addOne(15))
~~~
_____

2.
~~~python
def half(x):
    x /= 2
    return x
print(half(102))
~~~
_____

3.
~~~python
def average(a,b):
    return (a+b)/2
print(average(6,10))
~~~
_____

4.
~~~python
def cowsMoo(n):
    for i in n:
        print("Moo!")
cowsMoo(2)
~~~
_____
_____
_____
_____

5.
~~~python
def saveWhales(n, step):
    whalesSaved = 0
    for i in range(0, n, step):
        whalesSaved += 1
    return whalesSaved
    
print(saveWhales(10,2))
~~~
_____

6.
~~~python
def countCows(num):
    print("There are", num", "Cows")

countCows(4)
~~~
______
______
______

7.
~~~python
def batteryLife(t):
    batteryLife = 100
    batteryLife -= t*5
    return batteryLife
print(batteryLife(4))
~~~
_____

8.
~~~python
def price(items)
    dollars = items * 20
    return dollars + 1
print(price(10))
~~~
_____

9.
~~~python
def greeting(phrase)
    if phrase == "hello":
        print("Greetings Mate!")
    else:
    print("Well", phrase, "to you too!")

greeting("Howdy do")
~~~
_____

10.
~~~python
def workOut(time):
    calories = 0
    for i in range(time):
        calories += i
    return calories

print("I burned", workOut(10), "calories!")
~~~
_____

<br/>


## Section 2

1.


