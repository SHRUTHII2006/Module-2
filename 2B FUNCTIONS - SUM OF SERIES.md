# Exp.No:2b  
## FUNCTIONS - SUM OF SERIES

### AIM  

To create a Python Program to find the sum of series: 1 + x^2/2 + x^3/3 + … x^n/n using function. Get the input for n and x value and pass to the function.

### ALGORITHM

1.Begin the program

2.Input values for x and n

3.Define a function series_sum(x, n):

4.Initialize sum = 1

5.Use a loop from i = 2 to n

6.In each iteration, compute x^i / i and add to sum

7.Call the function with user input values

8.Display the result

9.End

### PROGRAM

def summation(n,x):

    sum1=1
    
    for i in range(2,n+1):
    
        sum1=sum1+((x**i)/i)
        
    print("The sum of series is",round(sum1,2))
    

n=int(input())

x=int(input())

summation(n,x)


### OUTPUT

![image](https://github.com/user-attachments/assets/29c5382d-88a7-4b1b-8de6-229c0524a8ce)


### RESULT

Thus the Python Program to find the sum of series: 1 + x^2/2 + x^3/3 + … x^n/n using function. Get the input for n and x value and pass to the function was written and excecuted successfully.
