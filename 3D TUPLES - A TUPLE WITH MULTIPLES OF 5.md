# Exp.No:3d TUPLES - A TUPLE WITH MULTIPLES OF 3
# AIM
To create a tuple of multiples of 3 up to N and print the tuple and its length.

# ALGORITHM
1. Start the program.
2. Accept input from the user for the value of N. Initialize an empty list a. Loop from 1 to N - 1:
3. For each number i, check if it is divisible by 3 using i % 3 == 0
4. If true, append i to the list a. Convert the list a into a tuple b.
5. Print the tuple b. Print the length of the tuple using len(b).
6. End the program.

# PROGRAM
# 212223060113-Karnatm Bindu

```
n=int(input())
a=[]
sum=0
for i in range(3,n):
    if(i%3==0):
        a.append(i)
        sum+=i
b=tuple(a)
print(b)
print(f"Sum is",sum)
```
# OUTPUT
<img width="1187" height="354" alt="image" src="https://github.com/user-attachments/assets/5fd95c27-b481-4e68-97a9-e31113fc73a2" />

# RESULT
Thus the program to create a tuple of multiples of 9 up to N and print the tuple and its length has been implemented and executed successfully.

