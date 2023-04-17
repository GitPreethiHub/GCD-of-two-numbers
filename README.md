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
# Program to find the gcd of a number using function
#Developed by: Preethi M
#Register no: 212222100037
def gcd():
    a,b=int(input()),int(input())
    if a>b:
        s=a
    else:
        s=b
    for i in range(1,s+1):
        if a%i==0 and b%i==0:
            hcf=i
    print("GCD of two numbers is:",hcf)

```

## Output:


![image](https://user-images.githubusercontent.com/119475585/232391106-a2af8e2d-1945-4737-bd4b-f0d545aa54f4.png)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
