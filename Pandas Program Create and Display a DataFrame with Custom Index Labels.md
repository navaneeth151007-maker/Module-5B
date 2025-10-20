# Pandas Program: Create and Display a DataFrame with Custom Index Labels

## 🎯 Aim

To create and display a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows.

---

## 🧠 Algorithm

1. **Import Libraries**: Import the required libraries – `pandas` and `numpy`.
2. **Create Dictionary**: Define a dictionary `exam_data` with keys: `'name'`, `'score'`, `'attempts'`, and `'qualify'`.
3. **Index Labels**: Create a list of custom index labels called `labels`.
4. **Create DataFrame**: Use `pd.DataFrame()` to create the DataFrame by passing the dictionary and index labels.
5. **Display Output**: Display the DataFrame using `print()` or by simply calling the DataFrame variable.

---

## 💻 Program
```c
import pandas as pd
data = {
    'Name': ['Alice', 'Bob', 'Charlie', 'David'],
    'Age': [25, 30, 22, 28],
    'City': ['New York', 'Los Angeles', 'Chicago', 'Houston']
}
index_labels = ['a', 'b', 'c', 'd']
df = pd.DataFrame(data, index=index_labels)
print("DataFrame with Custom Index Labels:")
print(df)

```
## Output
<img width="421" height="178" alt="image" src="https://github.com/user-attachments/assets/b8c31654-2bf3-4a00-a6c3-9144a93e9100" />

## Result
Thus, the program has been executed successfully.

