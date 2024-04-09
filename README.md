# Find the GCD of two numbers

NAME : VISHNU KM
DEPARTMENT : AI/ML
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
![exp 3 python](https://github.com/drgbhuvaneswari/GCD-of-two-numbers/assets/151489368/253667e3-739d-42a2-acb2-d3997c545fc4)

![exp 3 python](https://github.com/drgbhuvaneswari/GCD-of-two-numbers/assets/151489368/6211ff70-575e-4dce-90f6-f61c94d9c164)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
