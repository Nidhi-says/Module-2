# Exp.No:2b  
## FUNCTIONS - PERFECT NUMBER

### AIM  
To write a Python program to check if a number is a Perfect number using the concept of functions.

### ALGORITHM

1. Begin the program.  
2. Read the number `num` from the user using `input()`.  
3. Convert the input to an integer.  
4. Define the function `perfectNumber(num)` with the following steps:  
    - Initialize a variable `sum_of_divisors` to 0.  
    - Iterate through all numbers from 1 to `num//2` (as divisors of a number can't be greater than half of it).  
    - If a number `i` divides `num` perfectly (i.e., `num % i == 0`), add `i` to `sum_of_divisors`.  
    - If `sum_of_divisors` is equal to `num`, then print the number is a perfect number. Otherwise, print it's not a perfect number.  
5. Terminate the program.

### PROGRAM
```
def is_perfect_number(num):
    sum_of_divisors = 0
    for i in range(1, num):
        if num % i == 0:  
            sum_of_divisors += i
    if sum_of_divisors == num:
        return True
    else:
        return False
num = int(input())
if is_perfect_number(num):
    print("The number is a Perfect number!")
else:
    print("The number is not a Perfect number!")
```
### OUTPUT
![image](https://github.com/user-attachments/assets/29069ada-0612-4712-8084-9b4a7f4a79f9)

### RESULT
Thus a Python program to check if a number is a Perfect number using the concept of functions is implemented successfully.
