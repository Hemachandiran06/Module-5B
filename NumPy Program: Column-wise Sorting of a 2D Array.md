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
```
import numpy as np
original_array = np.array([[12, 5, 34],
                           [7, 23, 11],
                           [4, 18, 29]])
sorted_array = np.sort(original_array, axis=0)
print("Original Array:")
print(original_array)

print("\nColumn-wise Sorted Array (Ascending):")
print(sorted_array)
```
## Output
![Screenshot 2025-05-02 225638](https://github.com/user-attachments/assets/54137402-5ea9-44ec-9e4f-542b690ffcb3)

## Result
Thus,the python program Code Execution Successful 
