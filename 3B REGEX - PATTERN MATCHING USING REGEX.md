# Exp.No:3b REGEX - PATTERN MATCHING USING REGEX
# AIM
To write a Python program that matches a string containing only a certain set of characters (in this case a-z, A-Z and 0-9) using regular expressions.

# ALGORITHM
1. Start Input the string → str1 Define the allowed character set → allowed = [a–z, A–Z, 0–9] For each character ch in str1:
2. If ch is not in the allowed set → Return False (string contains invalid characters) If loop completes without invalid characters → Return True
3. End

# PROGRAM
# 212223060113- Karnatam Bindu
```
import re 
s=input()
if re.search(r'^[a-zA-Z0-9]+$',s):
    print(True)
else:
    print(False)
```
# OUTPUT
<img width="1192" height="347" alt="image" src="https://github.com/user-attachments/assets/e86afb83-8e8d-42a6-ad15-d88a461b01e0" />

# RESULT
Thus the program matches a string containing only a certain set of characters (in this case a-z, A-Z and 0-9) using regular expressions has been implemented and executed successfully.

