# Ex 5d:Pandas Program: Left Join of Two DataFrames in Pandas
## AIM
To write a Python Pandas program to perform a left join on two DataFrames using keys from the left DataFrame only.

## ALGORITHM
1) Start the program.
2) Create the first DataFrame with a key column.
3) Create the second DataFrame with a matching key column.
4) Use the Pandas merge() function with how='left'.
5) Perform the join based on the key column.
6) Display the resulting joined DataFrame.
7) End the program.

## Program
```
import pandas as pd

data1 = eval(input())
data2 = eval(input())

df1 = pd.DataFrame(data1)
df2 = pd.DataFrame(data2)

print("Original DataFrames:")
print(df1)
print("--------------------")
print(df2)

print("\nMerged Data (keys from data1):")
left_merge = pd.merge(df1, df2, on=['key1', 'key2'], how='left')
print(left_merge)

print("\nMerged Data (keys from data2):")
right_merge = pd.merge(df2, df1, on=['key1', 'key2'], how='left')
print(right_merge)

```

## Output
<img width="1108" height="461" alt="image" src="https://github.com/user-attachments/assets/ca94fdfc-3691-4221-9473-54baa14f8be4" />

## Result
Thus, the Pandas program successfully performed a left join between two DataFrames, retaining all records from the left DataFrame and matching data from the right DataFrame.
