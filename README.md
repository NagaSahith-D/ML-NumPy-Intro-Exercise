## NumPy Exercise
This repository contains the exercises I completed while learning and practicing **NumPy**, one of the core Python libraries for numerical and data manipulation tasks.  
All the code was written and executed inside the Jupyter Notebook file **`exercise-NumPy.ipynb`**.
## Project Overview
I worked through this notebook to understand the fundamentals of NumPy arrays ie how to create them, reshape them, and perform mathematical and logical operations.  
The exercises also involved exploring array attributes and integrating NumPy with simple datasets to perform small analysis tasks.
## Datasets Used
During this exercise, I used the following datasets to test and understand NumPy operations:
- `car-sales.csv`  
- `car-sales-extended.csv`  
- `car-sales-DataFrame-exported.csv`  
- `car-sales-missing-dropped.csv`
These files were used to convert raw tabular data into NumPy arrays and to perform array-based analysis and computations.
## Topics and Syntax Practiced
### 1. Importing Libraries
import numpy as np
import pandas as pd
### 2.Operations I Performed
•	I imported NumPy as its abbreviation 'np'.  
•	I created a 1-dimensional NumPy array using `np.array()`.  
•	I created a 2-dimensional NumPy array using `np.array()`.  
•	I created a 3-dimensional NumPy array using `np.array()`.  
•	I explored the attributes of a 1-dimensional array such as shape, number of dimensions, data type, size, and type.  
•	I explored the attributes of a 2-dimensional array.  
•	I explored the attributes of a 3-dimensional array.  
•	I imported pandas and created a DataFrame out of one of the arrays I had created.  
•	I created an array of shape (10, 2) filled with ones.  
•	I created an array of shape (7, 2, 3) filled with zeros.  
•	I created an array within a range of 0 and 100 with a step of 3.  
•	I created a random array with integers between 0 and 10 of size (7, 2).  
•	I created a random array of floats between 0 and 1 of shape (3, 5).  
•	I set the random seed to 42 for reproducibility.  
•	I created a random array of integers between 0 and 10 of size (4, 6).  
•	I created another array of random integers between 1 and 10 of size (3, 7) and saved it to a variable.  
•	I found the unique numbers in the array I had created.  
•	I accessed the 0th index of the latest array I had created.  
•	I selected the first two rows of the latest array.  
•	I selected the first two values of the first two rows of the latest array.  
•	I created a random array of integers between 0 and 10 and another array of ones, both of size (3, 5), and saved them to variables.  
•	I added the two arrays together.  
•	I created another array of ones of shape (5, 3).  
•	I attempted to add the array of ones and the other most recent array together.  
•	I created another array of ones of shape (3, 5).  
•	I subtracted the new array of ones from the most recent array.  
•	I multiplied the ones array with the latest array.  
•	I raised the latest array to the power of 2 using `**`.  
•	I performed the same operation using `np.square()`.  
•	I found the mean of the latest array using `np.mean()`.  
•	I found the maximum value of the latest array using `np.max()`.  
•	I found the minimum value of the latest array using `np.min()`.  
•	I found the standard deviation of the latest array.  
•	I found the variance of the latest array.  
•	I reshaped the latest array to `(3, 5, 1)`.  
•	I transposed the latest array.  
•	I created two arrays of random integers between 0 and 10 — one of size (3, 3) and the other of size (3, 2).  
•	I performed a dot product on these two arrays.  
•	I created two more arrays of random integers between 0 and 10, both of size (4, 3).  
•	I performed a dot product on these two arrays.  
•	I took the latest two arrays, transposed one of them, and then performed a dot product on them.  
•	## Array Comparisons
•	I created two arrays of random integers between 0 and 10 of the same shape and saved them to variables.  
•	I compared the two arrays using `>`.  
•	I compared the two arrays using `>=`.  
•	I found which elements of the first array were greater than 7.  
•	I compared both arrays using `==` to find which elements were equal.  
•	I sorted one of the arrays in ascending order.  
•	I sorted the indexes of one of the arrays.  
•	I found the index with the maximum value in one of the arrays.  
•	I found the index with the minimum value in one of the arrays.  
•	I found the indexes with the maximum values down the first axis (`axis=1`) of one of the arrays.  
•	I found the indexes with the minimum values across the zero axis (`axis=0`) of one of the arrays.  
•	I created an array of normally distributed random numbers.  
•	I created an array with 10 evenly spaced numbers between 1 and 100.  

### 3. Creating Arrays
•	python
•	Copy code
•	np.array([1, 2, 3, 4, 5])
•	np.arange(0, 10)
•	np.zeros((3, 3))
•	np.ones((2, 4))
•	np.random.randint(0, 100, size=(5, 5))
•	np.random.random((2, 3))

### 4. Inspecting Array Attributes
•	array.shape
•	array.ndim
•	array.size
•	array.dtype
•	type(array)
### 5. Basic Array Operations
•	array + 10
•	array - 5
•	array * 2
•	array / 3
•	array1 + array2
•	array1 * array2
### 6. Broadcasting and Comparisons
•	array > 10
•	array == 5
•	np.array_equal(array1, array2)
### 7. Reshaping and Transposing
•	array.reshape(3, 2)
•	array.T
### What I Learned
Through this exercise, I understood how the NumPy library works, how to manipulate and analyze data efficiently(and plot using matplotlib), and how these concepts form the foundation for creating machine learning models.
