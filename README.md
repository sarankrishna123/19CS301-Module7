# 19CS301-Module7
EX: 7.1 RECURSION
### Aim: To Write a Python Program to find the sum of all digits in a number using recursion
### Algorithm:
STEP 1: Start.

STEP 2: Define a function.

STEP 3: Create a base case for termination of the function. STEP 4: Create a recursive case to calculate the result.

STEP 5: Print the result. STEP 6: Stop.

### Program:
```
reg no:212223070023
name:Saran Krishna P S 
def sum_digit(n):
       if n<=0:
            return 0
       else:
            return n%10+sum_digit(n//10)
n = int(input())
sum = sum_digit(n)
print(sum)
```
### Output:
![image](https://github.com/user-attachments/assets/f8a856c5-040c-441e-b28e-9f3882bd6410)


### Result: Thus, the given program is implemented and executed successfully .
 

EX: 7.2 TYPES OF RECURSIONS
### Aim: To Write a Python Program to find the sum of all digits in a number using recursion
### Algorithm:
STEP 1: Start.

STEP 2: Define a function.

STEP 3: Create a recursive case in the first line of function for head recursion.

STEP 4: Print the result.

STEP 5: Stop.
### Program:
```
reg no:212223070023
name:Saran Krishna P S 
def fun(n):
     if (n >0):
          fun(n - 2)
      print(n-1, end=" ")
x = int(input())
if(x%2==0):
     fun(x)
else:
     fun(x+1)

```
### Output:
![image](https://github.com/user-attachments/assets/2f834f51-5958-4f87-8408-664802f90d1c)

###Result: Thus, the given program is implemented and executed successfully.
 


EX: 7.3 TAYLOR SERIES

###Aim: To python program to evaluate the series using recursion by collecting the x and n values from the user.
### ALGORITHM:
STEP 1: Start.

STEP 2: Create a variable x and n.

STEP 3: Get the values of x and n from user.

STEP 4: Create a base case and recursive case to calculate the result.

STEP 5: Print the result.

STEP 6: Stop.
### Program:
```
reg no:212223070023
name:Saran Krishna P S 
def series(x,n):
         if n==0:
            return 1
         else:
            return x**n/n+series(x,n-1)
x = int(input())
n = int(input())
print(series(x,n))
```
### Output:
![image](https://github.com/user-attachments/assets/1a43172d-a781-4ed3-a521-0e2442554b40)


 
### Result: Thus, the given program is implemented and executed successfully .
 

EX: 7.4 Solve by recursion relation

### Aim: To Write a Python Program to find whether a string is a palindrome or not using recursion

### Algorithm:
STEP 1: Start.

STEP 2: Define a function.

STEP 3: Create a base case and recursive case to calculate the result.

STEP 4: Create a variable and get input from user.

STEP 5 : Call the function.

STEP 6: Print the result.

STEP 7: Stop.

### Program:
```
reg no:212223070023
name:Saran Krishna P S 
def is_palindrome(word):
      if len(word)<1:
            return True
      else:
            if word[0]==word[-1]:
                 return is_palindrome(word[1:-1])
             else:
                  return False
word = str(input())
if is_palindrome(word)==True:
        print("String is a palindrome")
else:
        print("String is not a palindrome")
```
### Output:
![image](https://github.com/user-attachments/assets/e2ac4f00-07dd-4157-afae-546683822c56)

### Result: Thus, the given program is implemented and executed successfully .
 

