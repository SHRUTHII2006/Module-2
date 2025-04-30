# Exp.No:2c
## BUILT-IN FUNCTIONS AND LAMBDA FUNCTIONS - RELATING TWO NUMBERS


### AIM  

To write a Python program to check the relation between two numbers — whether one number is greater than, equal to, or lesser than another — using a lambda function.

### ALGORITHM

1. Begin the program.  
2. Use `eval()` to get two numbers (`num1` and `num2`) from the user.  
3. Define a lambda function `max` that takes two arguments `x` and `y`.  
4. The lambda function compares the numbers and prints:
   - If `x > y`, then it prints: "`num2` is smaller than `num1`".
   - Otherwise, it prints: "`num1` is smaller than `num2`".
5. Call the lambda function by passing `num1` and `num2` as arguments.  
6. Terminate the program.


### PROGRAM

result = lambda x,y : f"{x} is smaller than {y}" if x < y else (f"{x} is greater than {y}" if x > y else f"{x} is equal to {y}")

a=int(input()) 

b=int(input())

print(result(a, b))


### OUTPUT

![image](https://github.com/user-attachments/assets/efd84727-abc4-420e-9361-0a9d0533d182)


### RESULT
 THus the python program to check the relation between two numbers — whether one number is greater than, equal to, or lesser than another — using a lambda function was written and executed successfully.
