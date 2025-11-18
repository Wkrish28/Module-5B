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
student_data1=pd.DataFrame(eval(input()))
student_data2=pd.DataFrame(eval(input()))

print("Original DataFrames:")
print(student_data1)
print("-------------------------------------")
print(student_data2)

print("\nJoin the said two dataframes along rows:")
result_data=pd.concat([student_data1, student_data2])
print(result_data)
```
## Output
<img width="1182" height="875" alt="image" src="https://github.com/user-attachments/assets/77e2cd9b-1e14-48ea-b03d-30d118365e55" />

## Result
Thus the program using Pandas to join two DataFrames along rows (row-wise concatenation) and assign all data to a new DataFrame has been executed successfully
