# Exp.No:2c
## BUILT-IN FUNCTIONS AND LAMBDA FUNCTIONS - GREATEST OF TWO NUMBERS
### AIM  
To write a Python program to check the greatest number between two numbers using a lambda function.

### ALGORITHM

1. Begin the program.  
2. Use `eval()` to get two numbers (`num1` and `num2`) from the user.  
3. Define a lambda function `greatest` that takes two arguments `x` and `y`.  
4. The lambda function compares the numbers and prints:
   - If `x > y`, then it prints: "`The greatest number is: num1`".
   - Otherwise, it prints: "`The greatest number is: num2`".
5. Call the lambda function by passing `num1` and `num2` as arguments.  
6. Terminate the program.

---

### PROGRAM

```
num1 = int(input())
num2 = int(input())
greatest = lambda x, y: x if x > y else y
print(f"The greatest number is: {greatest(num1, num2)}")
```

### OUTPUT
![image](https://github.com/user-attachments/assets/d8dd02cc-f804-44d6-9fe9-f357077719a2)

### RESULT
Thus a Python program to check the greatest number between two numbers using a lambda function is implemented successfully.

