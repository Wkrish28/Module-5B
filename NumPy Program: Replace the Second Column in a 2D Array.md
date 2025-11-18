# NumPy Program: Replace the Second Column in a 2D Array

## 🎯 Aim
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.

## 🧠 Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Delete Column**: Use `np.delete()` to remove the second column (index 1) from the original array.
4. **Insert Column**: Use `np.insert()` to insert the new column at the second column's original position.
5. **Display Result**: Print the updated array with the replaced column.

## 🧾 Program

```
import numpy as np
a=eval(input())
b=np.array(a)
c=np.min(a,axis=1)
d=np.max(a,axis=0)
print("Printing Original array")
print(b)
print("Printing amin Of Axis 1")
print(c)
print("Printing amax Of Axis 0")
print(d)
```

## Output
<img width="1180" height="597" alt="image" src="https://github.com/user-attachments/assets/bdfb58fc-4295-4be4-8203-80be1f442d10" />

## Result
Thus the python program to print max from axis 0 and min from axis 1 from the given 2-D array has been executed successfully.
