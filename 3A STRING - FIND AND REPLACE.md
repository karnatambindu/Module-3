# Exp.No:3a STRING - ACCEPT AND JOIN CHARACTERS OF STRING
# AIM
To write a Python program to Count the common characters in the Two Inputted Strings "mobile" and "laptop".

# ALGORITHM
1. Start Input the first string → str1 Input the second string → str2 Initialize an empty list or set → common_chars For each character ch in str1:
2. If ch is also present in str2 And ch is not already in common_chars Then add ch to common_chars Display all characters in common_chars as common characters.
3. End

# PROGRAM
212223060113-Karnatam Bindu
```
def cc(s1,s2):
    ccc=[char for char in s1 if char in s2]
    for char in ccc:
        print(char)
    if ccc:
        print("are the common characters")
    else:
        print("There are no common characters")
s1=input()
s2=input()
cc(s1,s2)
```
# OUTPUT
<img width="1213" height="544" alt="image" src="https://github.com/user-attachments/assets/d55c0e58-8016-40d0-8368-ee3c22fc25d0" />

# RESULT
Thus the program that defines a function to Count the common characters in the Two Inputted Strings has been implemented and executed successfully.
