# Ex 5a:NumPy Program:Variance of a NumPy Array
## Aim
To write a NumPy program that reads a 2D array from the user and computes its variance.

## Algorithm

1.Start the program.

2.Read the 2D list input from the user using eval().

3.Convert the list into a NumPy array.

4.Use numpy.var() to compute the variance.

5.Display the result.

6.End the program.

## Program
```
import numpy as np
import ast

arr = np.array(ast.literal_eval(input()))
result = np.var(arr)
print(result)


```

## Output
<img width="512" height="150" alt="image" src="https://github.com/user-attachments/assets/bdd4407c-c86c-4539-8a26-d8965bd0f593" />

## Result
Thus, the NumPy program successfully computed the variance of the given array.
