# Phyton_Learning_Week2

## FUNCTION
In Python, a function is a block of reusable code that performs a specific task. Functions allow you to break down your program into smaller, manageable pieces, making your code more modular, readable, and easier to maintain.

![Cuplikan layar 2024-04-16 104653](https://github.com/alnimashakiya/Phyton_Learning_Week-2/assets/165742697/9ef2bb60-2ccb-4820-8bc0-1a03f5c4a79e)

Let's break down the components:

- def: It's a keyword used to define a function.
- function_name: It's the name of the function. Choose a descriptive name that reflects the purpose of the function.
- parameters: They are optional, and you can pass zero or more parameters to a function. Parameters are variables that receive values when the function is called.
- docstring: It's an optional string literal that describes what the function does. It's good practice to include a docstring to document the purpose, usage, and parameters of the function.
- Function body: It's the block of code inside the function where you write the operations to be performed.
- return: It's a keyword used to return a value from the function. The return statement is optional, and if omitted, the function returns None.
- result: It's the value returned by the function.

![Cuplikan layar 2024-04-16 105149](https://github.com/alnimashakiya/Phyton_Learning_Week-2/assets/165742697/e7efe95a-6fe2-4070-ba0b-7acfd96e7927)

#### Return 
In Python, the return statement is used within a function to exit the function and return a value or an expression to the caller. When a return statement is encountered in a function, the function's execution is terminated immediately, and control is passed back to the point where the function was called from.

![Cuplikan layar 2024-04-16 105349](https://github.com/alnimashakiya/Phyton_Learning_Week-2/assets/165742697/a9e54607-9671-461e-8e92-e1fef858b2c4)

#### Modify
To modify a list within a function in Python, you can pass the list as an argument to the function and make changes to it directly within the function. Since lists are mutable objects in Python, any modifications made to the list inside the function will affect the original list.

![Cuplikan layar 2024-04-16 105525](https://github.com/alnimashakiya/Phyton_Learning_Week-2/assets/165742697/81fd341b-5120-4343-8037-f63e23835596)

## NUMPY
NumPy is a powerful numerical computing library for Python. It provides support for large, multi-dimensional arrays and matrices, along with a collection of mathematical functions to operate on these arrays efficiently.

![Cuplikan layar 2024-04-16 105703](https://github.com/alnimashakiya/Phyton_Learning_Week-2/assets/165742697/4b3741d9-d12c-425c-bf77-c6202bd51b45)

#### You can check NumPy version
NumPy version is the version number of the NumPy library being used. This version number provides information about the specific release of NumPy, including bug fixes, feature enhancements, and other changes that have been made in that version.

![Cuplikan layar 2024-04-16 105901](https://github.com/alnimashakiya/Phyton_Learning_Week-2/assets/165742697/bc815dd1-f21e-45b2-ae52-16b9117401f4)

### NumPy array
Arrays: NumPy provides the numpy.ndarray data structure, commonly known as arrays, which are similar to Python lists but more efficient for numerical computations. Arrays can have any number of dimensions and can hold elements of the same data type.

In the context of NumPy arrays, the terms "dimension," "row," and "element" refer to the main components of an array.

- Dimension: Dimension refers to the number of axes or levels that an array has. For example, a one-dimensional array has one dimension (single axis), a two-dimensional array has two dimensions (horizontal and vertical axes), and so on. The number of dimensions of an array can be viewed using the ndim attribute of the array.

![Cuplikan layar 2024-04-16 110128](https://github.com/alnimashakiya/Phyton_Learning_Week-2/assets/165742697/dd1eee6b-c168-4eac-bab0-7d4f22b2a3a3)

![Cuplikan layar 2024-04-16 110230](https://github.com/alnimashakiya/Phyton_Learning_Week-2/assets/165742697/029e9409-2f54-4540-a744-5875157ca802)

![Cuplikan layar 2024-04-16 110329](https://github.com/alnimashakiya/Phyton_Learning_Week-2/assets/165742697/9a75e6fd-aa3b-41d5-bf46-ca98c9aa70df)

- Row: In the context of two-dimensional arrays or higher, a row refers to a sequence of data that is horizontally located within the array. A row in a two-dimensional array consists of a set of data with the same dimension, for example, in a two-dimensional array, each row consists of the same number of elements. The number of rows in an array can be viewed using the shape attribute of the array.
- Element: An element is an individual value contained within an array. Each element in an array has a specific location or index that indicates its position within the array. These elements can be accessed using indexing or slicing. For example, in a two-dimensional array, each element is a single value located at the intersection of a row and column.

![image](https://github.com/alnimashakiya/Phyton_Learning_Week-2/assets/165742697/ab5ad194-095c-4b98-bd08-695de0720a8f)

#### Check how many dimensions the arrays have
To check how many dimensions an array has in Python using NumPy, you can use the ndim attribute of the NumPy array object. Here's how you can do it:

import numpy as np

##### Create an array
arr1 = np.array([1, 2, 3])         # 1-dimensional array
arr2 = np.array([[1, 2, 3],        # 2-dimensional array
                 [4, 5, 6]])
arr3 = np.array([[[1, 2, 3],       # 3-dimensional array
                  [4, 5, 6]],
                 [[7, 8, 9],
                  [10, 11, 12]]])

##### Check the number of dimensions
print("Dimensions of arr1:", arr1.ndim)
print("Dimensions of arr2:", arr2.ndim)
print("Dimensions of arr3:", arr3.ndim)

Output:

_Dimensions of arr1: 1_
_Dimensions of arr2: 2_
_Dimensions of arr3: 3_

In this example, we have three arrays arr1, arr2, and arr3 with different numbers of dimensions. We use the ndim attribute to check the number of dimensions of each array. The output shows that arr1 is a 1-dimensional array, arr2 is a 2-dimensional array, and arr3 is a 3-dimensional array.

### Example (dim, row, element)

![Cuplikan layar 2024-04-16 111058](https://github.com/alnimashakiya/Phyton_Learning_Week-2/assets/165742697/568344d5-03e9-4b58-81d2-ff8cd006e48b)


![Cuplikan layar 2024-04-16 110913](https://github.com/alnimashakiya/Phyton_Learning_Week-2/assets/165742697/9ffdb5f1-5a2d-41e6-944c-dfc101cce7be)

# PANDAS
In Python, Pandas is a powerful and widely used open-source library used for data manipulation and analysis. It provides easy-to-use data structures and data analysis tools for handling structured data. The primary data structures in Pandas are Series (one-dimensional labeled array) and DataFrame (two-dimensional labeled data structure with rows and columns).

## Object Series
A Series is a one-dimensional labeled array that can hold data of any type (integer, float, string, etc.). It is similar to a column in a DataFrame or a single column of data.

### Implicit Index
Implicit indexing refers to the default integer-based index labels automatically assigned to elements in a data structure. When you create a data structure like a list, tuple, or NumPy array without specifying custom index labels, it will have implicit indexing where elements are accessed using integer indices starting from 0.

#### Example

![image](https://github.com/alnimashakiya/Phyton_Learning_Week-2/assets/165742697/52042380-15c7-442e-ba19-07455cd13530)

### Explicit Index
Explicit indexing refers to the use of user-defined or custom index labels to access elements in a data structure. In this case, you specify meaningful labels for each element in the data structure, making it easier to access elements by their associated labels instead of relying on integer indices.

#### Example

![image](https://github.com/alnimashakiya/Phyton_Learning_Week-2/assets/165742697/393555e9-e653-45e2-86bb-0e850e15793b)

### Loc & ILoc
In Pandas, both loc and iloc are used for indexing and selecting data from a DataFrame or a Series:

loc:
loc is primarily label-based indexing, meaning that you use the actual index labels to select data.
- It accepts label-based inputs for both rows and columns.
- You can use it to select specific rows and columns by their labels.
- The syntax for loc is df.loc[row_labels, column_labels].
  
iloc:
iloc is primarily integer-based indexing, meaning that you use integer positions to select data.
- It accepts integer-based inputs for both rows and columns.
- You can use it to select specific rows and columns by their integer positions.
- The syntax for iloc is df.iloc[row_positions, column_positions].

#### Example

![image](https://github.com/alnimashakiya/Phyton_Learning_Week-2/assets/165742697/457a1980-4a4b-4ba1-9f7b-b23b41a59c06)

#### More Example

![image](https://github.com/alnimashakiya/Phyton_Learning_Week-2/assets/165742697/965a839c-b914-486b-89b0-6ea52620bbf4)

## Object Frame
It seems like you're referring to a DataFrame object in pandas. A DataFrame is a two-dimensional labeled data structure with columns that can hold different data types, similar to a spreadsheet or SQL table. It is one of the primary pandas data structures used for data manipulation and analysis.

### Example

![image](https://github.com/alnimashakiya/Phyton_Learning_Week-2/assets/165742697/e87d0538-1903-4402-945a-dd385db20fdd)

### Example Data Frame from File CSV

![image](https://github.com/alnimashakiya/Phyton_Learning_Week-2/assets/165742697/1bcad44d-b0b7-4a78-b576-fb509ee08e84)

# RANDOM LIBRARY
The random library in Python provides functionalities for generating random numbers. It's commonly used in various applications ranging from simulations to games to cryptography.
Here's a basic overview of some commonly used functions from the random module:

- random(): This function returns a random floating-point number in the range [0.0, 1.0).
- randint(a, b): Returns a random integer N such that a <= N <= b.
- choice(seq): Returns a random element from the non-empty sequence seq.
- shuffle(seq): Randomly shuffles the elements of the sequence seq in place.
- sample(population, k): Returns a k length list of unique elements chosen from the population sequence or set.
  
These are just a few functions from the random module. There are more functions available for different specific purposes like generating random choices from weighted distributions, generating random numbers with a specified distribution (normal distribution, for example), and more.

### Example

![image](https://github.com/alnimashakiya/Phyton_Learning_Week2/assets/165742697/6657583a-8cbd-4adc-9935-fa6be57c1a2a)

# DATETIME
In Python, the datetime module provides classes for manipulating dates and times. Here's an overview of how to use the datetime module:

## 1. Importing the datetime module
Before using any functionality from the datetime module, you need to import it:
_import datetime_

## 2. Date and Time Objects
The datetime module provides several classes for representing dates and times:
- datetime.date: Represents a date (year, month, day).
- datetime.time: Represents a time (hour, minute, second, microsecond).
- datetime.datetime: Represents both date and time.
- datetime.timedelta: Represents a duration or difference between two dates or times.
- datetime.timezone: Represents a time zone.
  
## 3. Creating Date and Time Objects
You can create date and time objects using the constructors provided by the datetime module:
   
![image](https://github.com/alnimashakiya/Phyton_Learning_Week2/assets/165742697/c63e455c-75e9-463a-8e97-6a8a949df179)

## 4. Formatting and Parsing
You can format date and time objects into strings using the strftime() method and parse strings into date and time objects using the strptime() function:

![image](https://github.com/alnimashakiya/Phyton_Learning_Week2/assets/165742697/e5022f65-59eb-48c4-a775-02a8cb470fba)

# TXT FILE
A text file, commonly known as a .txt file, is a file containing plain text in the form of a sequence of characters. Text files do not contain any special formatting like those found in document files (such as Microsoft Word or HTML files). This means that the text in a text file is typically stored in a simple format, without colors, styles, or other design elements.

Text files are one of the most common types of files used in computing. They are often used to store data in a human-readable or machine-readable text format. Examples of the use of text files include storing simple data, logs, program source code, system configurations, and much more.

Text files typically have the ".txt" extension at the end of the file name to indicate that it is a text file. However, in some cases, text files may also have different extensions depending on the type of data or format used.

## Here's how you can create a text file and write some content to it:

![image](https://github.com/alnimashakiya/Phyton_Learning_Week2/assets/165742697/4919c802-b4d5-42be-868d-abeecb6ebc79)

![image](https://github.com/alnimashakiya/Phyton_Learning_Week2/assets/165742697/c287cdeb-3345-4e65-877e-706d70a26212)

![image](https://github.com/alnimashakiya/Phyton_Learning_Week2/assets/165742697/7460e973-0a67-47ee-bd89-a04f50f91167)



