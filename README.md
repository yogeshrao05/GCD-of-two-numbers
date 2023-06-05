# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
/*
Program to find the gcd of two number using function.
Developed by:yogesh rao 
RegisterNumber: 212222110055 
*/
def gcd():
    n1=int(input())
    n2=int(input())

    if(n1>n2):
        smaller=n2
    else:
       smaller =n1
    for i in range(1,smaller+1):
        if(n1%i == 0 and n2%i == 0):
            gcd=i
    print("GCD of two numbers is:",gcd)
```
## output:
  
  ![2a](https://github.com/yogeshrao05/GCD-of-two-numbers/assets/122008288/9cfd9585-b83b-4b62-be25-ccc90131ef78)

## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
