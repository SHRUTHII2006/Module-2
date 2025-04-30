# Exp. No: 2a  
## ITERATIVE STATEMENTS – PRINTING ALL PRIME NUMBERS WITHIN THE GIVEN RANGE.

###  Aim

To create Python Program to print all prime numbers within a given range.

###  Algorithm

1.Begin the program.

2.Use input() to read the value of n (the upper limit) from the user.

3.Convert the input to an integer.

4.Display the message "Prime Numbers are :".

5.Use a for loop to iterate from 2 to n (inclusive), using a variable num.

6.In each iteration:

7.Assume num is prime.

8.Use another for loop from 2 to num-1:

9.If num is divisible by any of these values, it is not prime. Break.

10.If no divisors are found, print num.

11.Terminate the program.

###  Program

def isprime(n):

    if (n==1 or n==0):
    
        return False
        
    for i in range(2,n):
    
        if(n%i==0):
        
            return False
            
    return True


n=int(input())

for i in range (0,n):

    if (isprime(i)):
    
        print(i)


### OUTPUT

![image](https://github.com/user-attachments/assets/0cd87277-e862-4752-b42b-3d1354b62eac)


### RESULT

Thus the Python Program to print all prime numbers within a given range was written and executed successfully.
