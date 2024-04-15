# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```
#Program to find the square root for the given number using Newton's method
#Developed By: Priyadharshan S
#Reference No.: 212223240127
def newtons_sqrt(number, iterations=100):
    x = number  
    for _ in range(iterations):
        x = 0.5 * (x + number / x)  
    return x
number=float(input())
sqrt = newtons_sqrt(number)
print("Square root of the number:", sqrt)

```

## Output:

![image](https://github.com/S-Priyadharshan/Square-root-of-a-number/assets/145854138/0e5c67a6-0df3-42e3-95bb-7969128346b4)

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
