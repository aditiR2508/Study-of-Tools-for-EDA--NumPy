# Study-of-Tools-for-EDA--NumPy
# Experiment 8
## Aditi Rathore
## 25070123006
## EnTC A1
# Aim
## To study the NumPy library and perform basic operations on NumPy arrays.
________________________________________
# Objectives
## •	To create NumPy arrays
## •	To perform mathematical operations on arrays
## •	To understand array attributes and indexing
## •	To use built-in NumPy functions
________________________________________
# Software Requirements
## •	Python
## •	NumPy library
## •	Jupyter Notebook / Google Colab / Python IDE
________________________________________
# Theory
### NumPy, short for Numerical Python, is a library used for numerical computations. It provides a powerful N-dimensional array object and functions for performing mathematical operations efficiently.
## Advantages of NumPy:
### •	Faster than Python lists
### •	Requires less memory
### •	Supports vectorized operations
### •	Provides mathematical and statistical functions
________________________________________
# Procedure
## 1. Importing NumPy
### import numpy as np
________________________________________
## 2. Creating a NumPy Array
### a = np.array([10, 20, 30, 40])
### print(a)
________________________________________
## 3. Creating an Array with Zeros, Ones and Range
### print(np.zeros(4))
### print(np.ones(4))
### print(np.arange(1, 10, 2))
________________________________________
## 4. Checking Array Attributes
### a = np.array([[1, 2, 3], [4, 5, 6]])
### print(a.ndim)   ---> to check the number of dimensions
### print(a.shape)  ---> to check the size of an array
### print(a.size)   ---> for checking total number of elements
### print(a.dtype)  ---> to check the data type of the array
________________________________________
## 5. Reshape the Array
### a = np.array([1, 2, 3, 4, 5, 6])
### print(a.reshape(2, 3))
________________________________________
## 6. Mathematical Operations
### a = np.array([10, 20, 30])
### b = np.array([1, 2, 3])
### print(a + b)
### print(a - b)
### print(a * b)
### print(a / b)
________________________________________
## 7. Statistical Operations
### a = np.array([10, 20, 30, 40])
### print(np.mean(a))
### print(np.sum(a))
### print(np.max(a))
### print(np.min(a))
### print(np.std(a))
________________________________________
## 8. Indexing and Slicing
### a = np.array([10, 20, 30, 40, 50])
### print(a[1])
### print(a[1:4])
________________________________________
# Output
## •	NumPy arrays were created
## •	Mathematical operations performed successfully
## •	Statistical values calculated
## •	Array attributes displayed
________________________________________
# Conclusion
## Through this experiment, we have performed basic operations on NumPy arrays successfully.
