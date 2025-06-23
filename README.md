# Array-indexing-and-slicing
import numpy as np

arr1D = np.array([1, 2, 3, 4, 5])

arr2D = np.array([[1, 2, 3], [4, 5, 6]])

print("Element at index 2 in 1D Array:", arr1D[2])

print("Element at row 1, col 2 in 2D Array:", arr2D[1, 2])

print("slicing 1D array:", arr1D[2:5])

print("slicing row in 2D array:", arr2D[1,:])

print("slicing column 2D array:", arr2D[:,2])

O/P:

Element at index 2 in 1D Array: 3

Element at row 1, col 2 in 2D Array: 6

slicing 1D array: [3 4 5]

slicing row in 2D array: [4 5 6]

slicing column 2D array: [3 6]# Array-indexing-and-slicing
