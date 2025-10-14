# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

---

### AIM  
To write a Python program that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions.

---

### ALGORITHM

1. Begin the program.  
2. Accept a string `str1` from the user.  
3. Define the regular expression pattern as `r"[a]+b{2,3}"`.  
4. Use the `re.match()` function to check if the string `str1` matches the pattern.  
5. If a match is found, print `"Found a match!"`.  
6. If no match is found, print `"Not matched!"`.  
7. Terminate the program.

---

### PROGRAM

```python
import re
p='ab{2}'
a=input()
if re.search(p,a):
    print("Found a match!")
else:
    print("Not matched!")

```
### OUTPUT
<img width="656" height="218" alt="image" src="https://github.com/user-attachments/assets/43dc94ac-a2be-4f90-9281-d038817a11d2" />


### RESULT
Thus the python program for check the that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions has been implemented and executed successfully.
