# Exp.No:2c
## BUILT-IN FUNCTIONS AND LAMBDA FUNCTIONS - RELATING TWO NUMBERS

---

### AIM  
To write a Python program to check the relation between two numbers — whether one number is greater than, equal to, or lesser than another — using a lambda function.

---

### ALGORITHM

1. Begin the program.  
2. Use `eval()` to get two numbers (`num1` and `num2`) from the user.  
3. Define a lambda function `max` that takes two arguments `x` and `y`.  
4. The lambda function compares the numbers and prints:
   - If `x > y`, then it prints: "`num2` is smaller than `num1`".
   - Otherwise, it prints: "`num1` is smaller than `num2`".
5. Call the lambda function by passing `num1` and `num2` as arguments.  
6. Terminate the program.

---

### PROGRAM
```
#Reg.no 212222090015
#Name Medhamythri RS
a=int(input())
b=int(input())
f=lambda a,b: (f"{a} is smaller than {b}")  if a<b else(f"{a} is greater than {b}" if(a>b) else(f"{a} is equal to{b}"))
print(f(a,b))

```

### OUTPUT

<img width="734" height="224" alt="image" src="https://github.com/user-attachments/assets/80012b90-eb00-4b60-ab70-e32552da2415" />


### RESULT

Thus the Python program using a lambda function to compare two numbers and display their relation was executed successfully and the output was verified.
