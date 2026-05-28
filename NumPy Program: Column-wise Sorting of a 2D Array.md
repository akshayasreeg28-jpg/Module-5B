# 1.NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
import numpy as np
a=np.array([[9,2,7],[4,8,1],[6,3,5]])
print(a)
print(np.sort(a,axis=0))

## Output
<img width="508" height="468" alt="image" src="https://github.com/user-attachments/assets/7ab9ee66-6f1f-4ed7-b024-0be2134ae600" />

## Result
Thus to write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order is implemented.
