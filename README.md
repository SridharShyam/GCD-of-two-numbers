# Find the GCD of two numbers
NAME: SHYAM S
REF.NO: 23012478
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
Program to find the gcd of two number using function.
Developed by: SHYAM S
RegisterNumber: 23012478 
def gcd():
    a=int(input())
    b=int(input())
    if a<b:
        smaller=a
    else:
        smaller=b
    for i in range(1,smaller+1):
        if a%i==0 and b%i==0:
            gcd_value=i
    print("GCD of two numbers is:",gcd_value)
```

## Output:
![image](https://github.com/SridharShyam/GCD-of-two-numbers/assets/144871368/4017414c-e5d9-46f9-809e-b0a40d920726)

![Alt text](<Screenshot 2023-11-29 134704.png>)
## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
