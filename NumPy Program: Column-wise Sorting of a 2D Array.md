# 5a.NumPy Program: Column-wise Sorting of a 2D Array
# Name: Vembarasi.A.R
# Reg no: 212224220120
##  Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

##  Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

##  Program
```
import numpy as np
array = np.array(eval(input()))
print('Given array','\n',array)
print()
print(np.sort(array,axis=0))
```
## Output
<img width="901" height="588" alt="image" src="https://github.com/user-attachments/assets/5468d183-fdc8-4ae3-bd3a-7be142189c66" />


## Result
Thus,the python program has been executed successfully
