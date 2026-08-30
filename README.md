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
a=np.array(eval(input())) 
print("Given array") 
print(end=" ") 
print(a) 
print() 
print(np.sort(a,axis=0))
```

## Output
<img width="1005" height="429" alt="image" src="https://github.com/user-attachments/assets/401c210f-da98-4f3d-8027-d3f1da0a83f8" />


## Result
Thus the python program for sorting each column in numpy has been implemented and executed successfully.

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

Add code here
```
import numpy as np
l1=eval(input())
l2=eval(input())
x=np.array(l1)
y=np.array(l2)
print(np.where(x>y))
print(np.where(x == y))
```
## Output
<img width="846" height="179" alt="image" src="https://github.com/user-attachments/assets/e53f089f-b990-4bed-a9bc-d31f39292953" />

## Result
Thus the program was successfully executed.

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
orig=np.array(eval(input()))
new=np.array(eval(input()))
print("Printing Original array")
print(orig)
modif=np.delete(orig,1,axis=1)
print("Array after deleting column 2 on axis 1")
print(modif)
result=np.insert(modif,1,new,axis=1)
print("Array after inserting column 2 on axis 1")
print(result)
```
## Output

<img width="862" height="262" alt="image" src="https://github.com/user-attachments/assets/c33d0900-9f8c-4a28-836f-d8dc37eb0630" />

## Result
Thus,the program has been executed successfully.
