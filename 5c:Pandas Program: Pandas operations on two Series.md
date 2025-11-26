# Ex 5c:Pandas Program: Pandas operations on two Series

## Aim
To write a Python Pandas program to perform addition and subtraction on two user-given Series.
## Algorithm
1) Start the program.
2) Read the first list from the user using eval().
3) Read the second list from the user using eval().
4) Convert both lists into Pandas Series.
5) Perform addition of the two Series using the + operator.
6) Perform subtraction of the two Series using the - operator.
7) Display the results of addition and subtraction.
8) End the program.


## Program
```
import pandas as pd

a1 = pd.Series(eval(input()))
a2 = pd.Series(eval(input()))

print("Addition of two Series:")
print(a1 + a2)
print()

print("Subtraction of two Series:")
print(a1 - a2)
```
## Output
<img width="626" height="682" alt="image" src="https://github.com/user-attachments/assets/65e0e445-f8e1-4fa9-91c9-69f6d7721e48" />

## Result
Thus, the Pandas program successfully performed addition and subtraction operations on the two Series provided by the user.
