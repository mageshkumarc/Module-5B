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
```
import pandas as pd

student_data1 = {
    'student_id': ['S1', 'S2', 'S3'],
    'name': ['Alice', 'Bob', 'Charlie'],
    'marks': [85, 90, 95]
}

student_data2 = {
    'student_id': ['S4', 'S5'],
    'name': ['David', 'Eva'],
    'marks': [88, 92]
}

df1 = pd.DataFrame(student_data1)
df2 = pd.DataFrame(student_data2)

combined_df = pd.concat([df1, df2], axis=0)

print(combined_df)
```

## Output
![image](https://github.com/user-attachments/assets/981e2d11-ed0e-4c1a-a35f-db95ec3b316a)

## Result
Thus,the program is executed successfully
