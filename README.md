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
def gcd():
    num1=int(input())
    num2=int(input())
    if num1<num2:
        smaller=num1
    else:
        smaller=num2
    for i in range(1,smaller+1):
        if num1%i==0 and num2%i==0:
            gcdvalue=i
    print("GCD of two numbers is: {}".format(gcdvalue))
```

## Output:
![image](https://user-images.githubusercontent.com/119559022/232687211-534c47c3-25b9-4e7a-8e1b-08118e36f43e.png)
 
## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
