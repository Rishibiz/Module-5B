# Ex 5b:NumPy Program: Add 5 to NumPy elements greater than 40

## Aim
To write a NumPy program that adds 5 to all elements of an array that are greater than 40.

## Algorithm

1) Start the program.
2) Read the NumPy array from the user using eval().
3) Convert the input into a NumPy array using np.array().
4) Identify all elements greater than 40 using boolean indexing.
5) Add 5 to all elements that satisfy the condition.
6) Display the updated NumPy array.
7) End the program.
## Program
```
import numpy as np

arr = np.array(eval(input()))
arr[arr > 40] = arr[arr > 40] + 5
print(arr)
```

## Output
<img width="679" height="155" alt="image" src="https://github.com/user-attachments/assets/30e3a6a9-28ef-44ac-b143-53b7ee6d4094" />

## Result
Thus, the NumPy program successfully added 5 to all elements greater than 40.
