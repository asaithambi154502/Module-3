# Exp.No:3a
## STRING - REMOVE FORM STRING 

---

### AIM  
To write a Python function to accept a string and form a new string by removing all the vowels (both uppercase and lowercase) from the given string.
---

### ALGORITHM
1.Begin the program.
2.Define a function named remove(input_string).
3.Initialize a string variable vowels containing all vowel characters: "aeiouAEIOU".
4.Traverse each character in input_string using a loop or comprehension.
5.For each character, check if it is not in the vowels string.
6.If the character is not a vowel, include it in the new string result_string.
7.Join all non-vowel characters to form the final string.
8.Display the result_string.
9.Terminate the program.

---

### PROGRAM

```pyhton
def remove(input_string):
    vowels = "aeiouAEIOU"
    result_string = ''.join(char for char in input_string if char not in vowels)
    print(result_string)




```

### OUTPUT
<img width="796" height="269" alt="image" src="https://github.com/user-attachments/assets/c9516302-5021-4d26-a361-3f7ba31e248f" />


### RESULT
Thus the python program to accept a string and form a new string by removing all the vowels (both uppercase and lowercase) from the given string has been implemented and executed successfully.
