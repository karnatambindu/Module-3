# Exp.No:3c LIST - EVEN NUMBERS LIST
# AIM
To write a Python function that creates a list of even numbers from 12 to n and prints the list and its sum.

# ALGORITHM
1. Start the program.
2. Define a function named createlist that accepts a single parameter n.
3. Initialize an empty list l. Iterate from 12 to n-1 using a for loop: For each number i in the range: Check if i is even using the condition i % 2 == 0.
4. If the condition is true, append i to the list l. After the loop ends, print the list using print("List =", l).
5. Calculate the sum of the list using sum(l) and print the result.
6. End the function.
7. Terminate the program.

# PROGRAM
# 212223060113-Karnatam Bindu

```
def createlist(n):
    l=[]
    for i in range(12,n):
        if i%2==0:
            l.append(i)
    print("List =",l)
    print("Sum of the list",sum(l))
```
# OUTPUT
<img width="1256" height="312" alt="image" src="https://github.com/user-attachments/assets/d9d1b35f-8483-4946-abe2-3c31ea67655b" />

# RESULT
Thus the program that creates a list of even numbers from 12 to n and prints the list and its sum has been implemented and executed successfully.
