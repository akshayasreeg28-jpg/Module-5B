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

# # 2.NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

## 🎯 Aim
To write a Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y`.

## 🧠 Algorithm
1. **Import NumPy**: Import the NumPy library.
2. **Define Arrays**: Define two NumPy arrays, `x` and `y`, with the same shape (i.e., same number of elements).
3. **Use Boolean Indexing**: 
   - `x > y` gives a boolean array where elements of `x` are greater than `y`.
   - `x == y` gives a boolean array where elements of `x` are equal to `y`.
4. **Find Indices**: Use `np.where()` to get the indices where the conditions `x >= y` are satisfied.
5. **Print Indices**: Print the indices where the condition holds true.

## 🧾 Program
```
import numpy as np
x=np.array([4,8,2,6,9])
y=np.array([3,8,5,1,9])
print(np.where(x>=y))
```

## Output
<img width="353" height="335" alt="image" src="https://github.com/user-attachments/assets/edf8c1be-889d-4d22-a423-42c132db8070" />

## Result
Thus to write a Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y`.

# 3.NumPy Program: Replace the Second Column in a 2D Array

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
a=np.array([[1,2,3],[4,5,6],[7,8,9]])
b=np.array([10,11,12])
a=np.delete(a,1,axis=1)
a=np.insert(a,1,b,axis=1)
print(a)
```

## Output
<img width="507" height="402" alt="image" src="https://github.com/user-attachments/assets/94cbf677-5c56-487b-9a03-b1a49c21ca56" />

## Result
Thus to write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position is implemented.

# 4.Pandas Program: Create and Display a DataFrame with Custom Index Labels

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
```
import pandas as pd
import numpy as np
exam_data={'name':['Anu','Bala','Charan'],'score':[90,85,88],'attempts':[1,2,1],'qualify':['Yes','Yes','Yes']}
labels=['a','b','c']
df=pd.DataFrame(exam_data,index=labels)
print(df)
```
## Output
<img width="1010" height="426" alt="image" src="https://github.com/user-attachments/assets/497c1588-8008-42de-94e5-3810e85e7d1c" />

## Result
Thus to create and display a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows is implemented.

# 🧪5. Pandas Program: Join Two DataFrames Along Rows

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
student_data1={'Name':['A','B'],'Marks':[90,85]}
student_data2={'Name':['C','D'],'Marks':[88,92]}
df1=pd.DataFrame(student_data1)
df2=pd.DataFrame(student_data2)
df3=pd.concat([df1,df2],axis=0)
print(df3)
```

## Output
<img width="580" height="421" alt="image" src="https://github.com/user-attachments/assets/33b06604-1d44-4aaf-9c43-f44fe9f21d0e" />

## Result
Thus to write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame is implemented.



