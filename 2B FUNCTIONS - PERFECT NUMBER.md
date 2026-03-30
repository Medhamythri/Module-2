# Exp.No:2b  
## FUNCTIONS - PERFECT NUMBER

### AIM  
To write a Python program to check if a number is a Perfect number using the concept of functions.

---

### ALGORITHM

1. Begin the program.  
2. Read the number `n` from the user using `input()`.  
3. Convert the input to an integer.  
4. Define the function `perfectNumber(n)` with the following steps:  
    - Initialize a variable `factor_sum` to 0.  
    - Iterate through all numbers from 1 to `n//2` (as divisors of a number can't be greater than half of it).  
    - If a number `i` divides `n` perfectly (i.e., `n % i == 0`), add `i` to `factor_sum`.  
    - If `factor_sum` is equal to `n`, then print the number is a perfect number. Otherwise, print it's not a perfect number.  
5. Terminate the program.

---

### PROGRAM
```
#Reg.no 212222090015
#Name Medhamythri RS

def perfect_num(num):
  
    sume=0  
    for i in range(1,num):  
        if (num%i==0):  
            sume=sume+i  
    if(sume==num):  
        print("The number is a Perfect number!")  
    else:  
        print("The number is not a Perfect number!") 

num=int(input())
perfect_num(num)

```
### OUTPUT
<img width="962" height="249" alt="image" src="https://github.com/user-attachments/assets/e3c24ba6-e42e-42a4-8dfc-10fc0e20428d" />

### RESULT
Thus the Python program to check whether a number is a Perfect Number using functions was executed successfully and the output was verified.
