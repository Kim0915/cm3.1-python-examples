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
Fill in the blank to get the correct output

1. output: 10
~~~python
def sum(x,y):
    return _____
print(sum(4,6))
~~~
_____

2. output: 20
~~~python
def findCows(a,b):
    c = a + b
    d = c + _____
    return d
print(findCows(10,2))
~~~
_____
 
3. output: 12
~~~python
def countFrogs(n):
    frogs = 0
    for i in n:
        frogs += i // 2
    return frogs
print(countFrogs(_____))
~~~
_____

4. output: "Lion"
~~~python
def animalKingdom(n):
    if n == 1:
        return "Lion"
    elif n == 2:
        return "Frog"
    else:
        return "Dog"
print(_______)
~~~
_____

5. output: 25
~~~python
def square(x):
    return _____
print(square(5))
~~~
_____

<br/>


## Section 3
Write code in order to achieve the given task

1. Write a function called `addThree()`. The function should take three inputs. It should return the sum of those three inputs. 
For example, addThree(1,2,3) = 6.
_____
_____
_____
_____
_____
_____

2. Write a function called `kittens()`. The function should take one integer as input. The function will print "Meow" as many times as the integer given.
For example, kittens(3) = 
~~~console
Meow
Meow
Meow
~~~
_____
_____
_____
_____
_____
_____
_____

3. Write a function called `difference()`. The function should take the difference between two inputs.
For example, difference(16, 6) = 10.
_____
_____
_____
_____
_____
_____

4. Write a function called `countLegs()`. The function should take an integer `n` as input. The function will return the number of legs if there were `n` cows.
For example, countLegs(10) = 40. Since there are 10 cows, there are 40 legs.
_____
_____
_____
_____
_____
_____

5. Write a function called `purchase()`. The function should take three inputs. Add the third input to the first input. Subtract the third input from the second input. Then print out "Shop: {input1}" on the first line, and "Wallet: {input2}" on the second line.
For example: purchase(100,  60, 5) = 
~~~console
Shop: 105
Wallet: 65
~~~
_____
_____
_____
_____
_____
_____

## Section 4
Use input() to solve the following task:

1. Create a function called `spend()` that will take in one integer input, and return that integer minus 10. 
2. Set a variable `money` equal to 100
3. Create a while loop to do the following:
- ask the user if they would like to spend
- if the user says yes, run the spend function usig money, then print how much money they have left
- if the user says no, stop the loop and print how much money they have left
_____
_____
_____
_____
_____
_____
_____
_____
_____
_____
_____
_____

    
    

