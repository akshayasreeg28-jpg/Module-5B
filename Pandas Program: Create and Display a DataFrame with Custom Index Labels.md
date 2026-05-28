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
