# # NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

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

x=np.array(eval(input()))
y=np.array(eval(input()))

greater_position=np.where(x>y)
equal_position=np.where(x==y)

print(greater_position)
print(equal_position)

```
## Output

![Screenshot 2025-05-15 101254](https://github.com/user-attachments/assets/2a00ecbd-f2eb-444d-9d9e-d71d58ffd0f3)

## Result
Thus, the program is successfully execuited.
