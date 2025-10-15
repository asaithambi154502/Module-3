# Exp.No:3d  
## TUPLES - A TUPLE WITH MULTIPLES OF 5

---

### AIM  
To write a Python program to create a tuple containing all multiples of 5 up to a given number **N**.

---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `N` from the user.  
3. Use a generator expression inside the `tuple()` function to create a tuple `multiples_of_5` with values starting from `5` up to `N - 1`, stepping by `5`.  
4. Return the tuple `multiples_of_5`.  
5. Print the resulting tuple.  
6. Terminate the program.

---

### PROGRAM

```python

N = int(input())


multiples_of_5 = tuple(i for i in range(5, N, 5))


print(multiples_of_5)

```

### OUTPUT
<img width="893" height="257" alt="image" src="https://github.com/user-attachments/assets/c8e259a5-a487-4b7f-93d5-3a7b8ec8a1da" />


### RESULT
Thus the python program to create a tuple containing all multiples of 5 up to a given number **N**has been implemented and executed successfully.
