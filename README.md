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
/*
Program to find the square root for the given number(newton's method) using function.
Developed by: Meetha Prabhu
RegisterNumber: 22003992
def newton_method(n,n_i=100):
    a=float(n)
    for i in range(n_i):
        n=0.5*(n+a/n)
    return n
a=int(input())
print("Square root of the number:",newton_method(a))
*/
```
## Output:
![image](https://user-images.githubusercontent.com/119401038/234226064-c5635ac0-fd70-47b8-a84e-c827ca1419ad.png)

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
