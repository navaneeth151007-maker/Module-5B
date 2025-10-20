# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
```c
import numpy as np
arr = np.array([[5, 2, 9],
                [1, 8, 3],
                [7, 4, 6]])

print("Original Array:")
print(arr)

sorted_arr = np.sort(arr, axis=0)

print("\nColumn-wise Sorted Array:")
print(sorted_arr)

```

## Output
<img width="408" height="208" alt="image" src="https://github.com/user-attachments/assets/a83ec99a-b725-48d6-a15f-249ff0fea832" />

## Result
Thus, the program has been executed successfully.

