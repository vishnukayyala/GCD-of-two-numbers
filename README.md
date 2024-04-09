# Find the GCD of two numbers
NAME VISHNU KM
DEPARTMENT : AI / ML
REG NO : 212223240185

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
Developed by: VISHNU KM
RegisterNumber:  212223240185


def gcd():
    n1,n2=int(input()),int(input())
    if n1>n2:
        smaller=n2
    else:
        smaller=n1
    for i in range(1,smaller+1):
        if(n1%i==0 and n2%i==0):
            hcf=i
    print("GCD of two numbers is:",hcf)

```

## Output:
![exp 3 python](https://github.com/vishnukayyala/GCD-of-two-numbers/assets/151489368/1c52652d-b4c6-4407-bc1d-30c5c17f35d9)

![exp 3 python](https://github.com/vishnukayyala/GCD-of-two-numbers/assets/151489368/fefb1264-77f4-43b8-a850-866eaab4f793)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
