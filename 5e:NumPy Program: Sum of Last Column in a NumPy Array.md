# Ex 5e:NumPy Program: Sum of Last Column in a NumPy Array

## Aim
To write a NumPy program to compute the sum of the last column of a given NumPy array.
## Algorithm
1) Start the program.
2) Read the 2D array input from the user using eval().
3) Convert the input list into a NumPy array.
4) Select the last column using array slicing.
5) Use np.sum() to calculate the sum of the last column.
6) Display the result.
7) End the program.
## Program
```
import numpy as np

arr = np.array(eval(input()))
arr = arr.reshape(-1, 3)
print(arr)
print(arr[:, -1].sum())
```
## Output
<img width="607" height="305" alt="image" src="https://github.com/user-attachments/assets/c5e4a737-df74-42eb-8793-a73a2614ffa5" />

## Result
Thus, the NumPy program successfully computed the sum of the last column in the given array.
