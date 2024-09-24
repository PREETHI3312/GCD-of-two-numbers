# DATE:
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

Program to find the gcd of two number using function.
def gcd():
    n1,n2=int(input()),int(input())
    if n1>n2:
        small=n2
    else:
        small=n1
    for i in range(1,small+1):
        if(n1%i==0 and n2%i==0):
            hcf=i
    print(f"GCD of two numbers is: {hcf}")
```
# Developed by: A K PREETHI
# RegisterNumber:  212223230156



## Output:
![image](https://github.com/user-attachments/assets/ee7bc800-7fda-4ac6-8a0f-e9c779f164b4)




## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
