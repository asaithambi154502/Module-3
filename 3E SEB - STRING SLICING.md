# Exp.No:3e
## SEB - STRING SLICING

---

### AIM  
To write a Python function that accepts  a python function that accepts the string and prints every second item between 2 to 10.  and then prints the new string.

---

### ALGORITHM

1. Begin the program.  
2. Accept a string as input.  
3. Take a slice of the input string from index **2** to **10** (Python uses 0-based indexing, so index 2 refers to the 3rd character, i.e., the 4th character in natural terms).  
4. Reverse the sliced substring.  
5. Extract every second character from the reversed substring using slicing (`[::2]`).  
6. Print the final processed string.  
7. Terminate the program.

---

### PROGRAM

```python
def slice(str1):
    text=str1[2:10:2]
    print(f"The sliced string is '{text}'")
str1=""
```

### OUTPUT
<img width="1040" height="288" alt="image" src="https://github.com/user-attachments/assets/74f9a628-c41f-4a18-ae8c-e5c793e296a9" />


### RESULT
Thus the python program to create a python function that accepts the string and prints every second item between 2 to 10.  and then prints the new string
has been implemented and executed successfully.
