# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program
```c
import pandas as pd
df1 = pd.DataFrame({
    'Name': ['Alice', 'Bob'],
    'Age': [25, 30],
    'City': ['New York', 'Los Angeles']
})
df2 = pd.DataFrame({
    'Name': ['Charlie', 'David'],
    'Age': [22, 28],
    'City': ['Chicago', 'Houston']
})

print("DataFrame 1:")
print(df1)
print("\nDataFrame 2:")
print(df2)
df_combined = pd.concat([df1, df2], axis=0, ignore_index=True)
print("\nCombined DataFrame:")
print(df_combined)
```
## Output
<img width="442" height="346" alt="image" src="https://github.com/user-attachments/assets/7e0d4e4b-8f32-4d88-8cff-5797e7286067" />

## Result
Thus, the program has been executed successfully.

