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
~~~
import numpy as np
x = np.array([10, 5, 8, 12, 3])
y = np.array([7, 5, 10, 10, 4])
indices = np.where(x >= y)
print("Array x:", x)
print("Array y:", y)
print("Indices where x >= y:", indices)
print("Values from x where condition is true:", x[indices])
~~~

## Output
<img width="963" height="665" alt="Screenshot 2026-03-26 104942" src="https://github.com/user-attachments/assets/6a2e495d-5c64-4676-b008-ba686121a969" />

## Result
