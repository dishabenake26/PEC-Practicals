# Array Operations Using NumPy

## 📌 Overview

This practical focuses on implementing arrays using the **NumPy library in Python** and performing basic array, arithmetic, and statistical operations.

## 🎯 Aim

To implement arrays using NumPy in Python and perform basic array, arithmetic, and statistical operations.

## 🛠️ Software and Tools Used

* **Google Colab**
* **Python**
* **NumPy**
* **Web Browser**

## 📚 Topics Covered

* Importing NumPy
* Creating one-dimensional arrays
* Creating two-dimensional arrays
* Finding array size and dimension
* Basic arithmetic operations
* Array indexing
* Array slicing
* Mathematical and statistical operations

## 🔢 Array Operations

The practical demonstrates the following operations using NumPy:

### 1. Creating Arrays

A one-dimensional array is created using `np.array()`.

```python
import numpy as np

arr = np.array([10, 20, 30, 40, 50])
```

Two-dimensional arrays are also implemented using rows and columns.

### 2. Array Information

NumPy properties such as `size` and `ndim` are used to find the number of elements and dimensions of an array.

### 3. Arithmetic Operations

The practical performs:

* Addition
* Subtraction
* Multiplication
* Division

These operations are performed element-wise on the array.

### 4. Indexing

Array indexing is used to access individual elements. Python indexing starts from `0`.

Examples include accessing the first, third, and last elements.

### 5. Slicing

Array slicing is used to extract a portion of an array.

Examples include:

* Extracting the first three elements
* Extracting elements from a particular index

### 6. Statistical Operations

NumPy functions are used to perform numerical analysis:

* `np.sum()` — calculates the sum
* `np.mean()` — calculates the mean
* `np.max()` — finds the maximum value
* `np.min()` — finds the minimum value

## 💻 Complete Program

The practical combines array creation, array information, arithmetic operations, and statistical operations into one program.

```python
import numpy as np

marks = np.array([65, 70, 75, 80, 85])

print("Marks:", marks)

print("Number of elements:", marks.size)
print("Dimension:", marks.ndim)

print("Marks + 5:", marks + 5)
print("Marks * 2:", marks * 2)

print("Total Marks:", np.sum(marks))
print("Average Marks:", np.mean(marks))
print("Maximum Marks:", np.max(marks))
print("Minimum Marks:", np.min(marks))
```

## 🎓 Learning Outcomes

After completing this practical, I learned how to:

* Create one-dimensional and multidimensional NumPy arrays
* Find the size and dimension of an array
* Perform element-wise arithmetic operations
* Access array elements using indexing
* Extract elements using slicing
* Perform basic mathematical and statistical operations using NumPy

## 📁 Files

* `Implementation_of_Array_Using_NumPy.ipynb` — Google Colab/Jupyter Notebook containing the practical
* `README.md` — Description and documentation of the practical

## 👩‍💻 Author

**Disha**

---

*Data Science Practical — Array Operations Using NumPy*
