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
