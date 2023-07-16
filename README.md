# Python-Workshop
![Banner](img/Python%20Classroom%20Banner.jpg)


### Official Python Website:

[![Python](https://img.shields.io/badge/python_Official_Website-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://python.org) &nbsp;&nbsp;
[![Python](https://img.shields.io/badge/python_Official_Documentation-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://python.org) &nbsp;

<br>

[![License](https://img.shields.io/static/v1?label=License&message=MIT&color=red)](https://github.com/huggingface/diffusion-models-class/blob/main/LICENSE) &nbsp;
[![GitHub forks](https://img.shields.io/github/forks/dhakalnirajan/Python-Workshop.svg?style=social&label=Fork&maxAge=2592000)](https://github.com/dhakalnirajan/Python-Workshop) &nbsp;

<br>

[![Made with Python](https://img.shields.io/badge/Made%20with-Python-red?style=flat-square&logo=Python)](https://www.python.org/) &nbsp;
[![Made with Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-red?style=flat-square&logo=Jupyter)](https://jupyter.org/try) &nbsp;
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=flat-square&logo=visual-studio-code&logoColor=white)

# Objectives of the Course
1. To make students understand the use of Python in Research.
2. To teach the usage of python and its modules like 
    * **NumPy**, 
    * **Pandas**,
    * **Matplotlib**, 
    * **Seaborn**,
    * **SymPy**

<br>

This course starts from July 18, 2023 and the first working days are dedicated to learning basics of Programming using Python.

<br>

### Course:
1. Python Introduction (7 days)
    - Python Syntax
    - Data Types
    - Operators
    - Lists
    - Control statements
    - loops
    - functions
    - OOP: Python Class
    - Modules: NumPy, Matplotlib, Pandas


2. NumPy
    - Data as lists, arrays, and tuples.
    - Find the average, stddev, quartiles, mode, etc. of the data.


3. Matplotlib
    - Plotting Data from lists in NumPy.
    - Plot curves of polynomial functions, trigonometriv functions, etc.
    - Plotting subplots
    - Plotting scatter plots, bar charts, histograms, pie charts, etc.


4. Pandas
    - Read CSV
    - Dataframes
    - Analyzing Data
    - Pandas Correlations
    - Plotting Data


5. SymPy
    - Defining Functions
    - Derivatives
    - Integrals
    - Solving differential equations

<br>

# **Course Syllabus**:
---

## 1. Python Programming


- Introduction to Google Colab
- Python version and pip package manager
- Python Program
- Python Arithmatic Operators
- Using Python as calculators
- IEEE 754 standard for floating point arithmetic
- How to define a variable name and Variable Naming convention
- Changing and updating variable values in Python
- Data types in Python
- Number data type: int, float, complex
    - Number data type with conditionals
    - Anatomy of conditionals: if ... else statements
    - Indentation
    - Expression and Comparison operators
    - Nesting and chaining(if... elif... else) of conditionals
    - Logical Operators
- String data type in Python
    - Single line strings and multi-line strings
    - Indexing and slicing: How to access characters in a string?
    - range() method
    - for loop in python with range() method
    - continue vs break vs pass statements
    - characters vs substrings
    - string methods: `.replace(), .lower(), .upper(), .lstrip(), .rstrip(), .split()`
- Sequence data type: List
    - Indexing, slicing, for loop with and without `range()` , while loop, for loop vs while loop
    - Calculating mean of list using loops
    - Negative Indexing 
    - Membership operators: `in , not in`
    - Mutable vs Immutable data type with exmaple
    - List methods: `.insert(), .append(), .remove(), .pop(), .sort()`
    * List comprehension
* Sequence data type: Tuple
    * List vs tuple
    * Typecasting data types 
    * loop in tuple
    * Unpacking of tuples
* Sets: unordered, unindexed
    * `.remove() , .add()` in sets
    * Type conversion 
    * Set operation in Python : union, intersection, difference
* Mapping data type Dictionary
    * Accessing dictionary items and add key value pair
    * `keys() and values()` method in dictionary
    * Updating dictionary: The `update()` method 
    * `pop()
    * Looping in dictionary
    * Nested Dictionary


* NoneType data type in Python
    * Identity Operators

* Python Functions
    * def keyword and function arguments
    * return statement
    * Default arguments and non default arguments
    * Handling multiple return values
    * Recursion and its advantage

* Object Oriented Programming in Python (OOP)
    * Characterstics of OOP
    * Class and Object --defining class and creating object
    * . operator
    * Instance attribute vs class attribute
    * What is this `def __init__(self)` ?
    * What is `self` parameter?
    * `__new__()` and `__init__()`
    * Object methods or user defined methods inside user defined class
    * Inheritance in Python
    * `super()` method
    * Polymorphism and operator overloading
    * Abstraction and Encapsulation
    * limiting behaviour of variables : private, public and protected


## 2. Numpy


* Install and check version of the numpy
* How to import numpy?
* Vectors, the 1D Arrays 
    * What is array and Creating Numpy array: How do you know the shape and size of an array?
    * What’s the difference between a Python list and a NumPy array?
    * Array creation routines: `.zeros(), .ones() and .empty()`
    * Array initilization using Monotonic sequence : `.arange() , .linspace()
    * Creating random array: `np.random.randint(), np.random.rand(), np.random.uniform(), np.random.randn(), np.random.normal()`
    * Indexing (fancy indexing) and slicing 1D numpy array
    * Logic Functions: Truth value testing : `np.any() vs np.all()`
    * Adding, concatenate, and sorting array elements `np.append() , np.sort(), np.concatenate()`
    * Vector operations i.e. elementwise operations in 1D numpy array 
    * Broadcasting and its application in Image Processing
    * Array Operation: `np.floor(), np.ceil(), np.round()`
    * Statistics using numpy: `.max(), .min(), .argmax(), .argmin(), .sum(), .mean(), .std(), .var()`

* Matrices, the 2D Arrays, and 3D arrays + Introduction to Computer vision

    * Creation of 2D numpy array using: `list of list and 1D array, .ones(), .zeros(), .full(), .eye(), .reshape()`
    * Indexing, slicing and modifying values in 2D array
    * Creating random matrix: `np.random.randint(), np.random.rand(), np.random.uniform(), np.random.randn(), np.random.normal()`
    * Matrix multiplication: Dot product
    * Cross Product
    * Inverse, Transpose and determinant of matrix using numpy
    * The `axis` argument in numpy: 2D: `axis = 0 vs axis = 1`
    * Matrix statistics: `.min(), .min(axis = 1), .min(axis = 0), .argmin(), .argmin(axis = 1), .argmin(axis = 0), np.unravel_index(),  `
    * How morden day images are created? with Example of opencv library

## 3. Matplotlib

* Install and check version of matplotlib
* how to import matplotlib
* 2D plotting
  * Line plot
  * Scatter plot
  * Bar plot
  * Histogram
  * Pie chart
  * Box plot
  * Density plot
  * Meshgrid
  * Contourplot
* Subplots
* Customizing plots
  * Title, Axis labels, Legend, Figure size,
  * Spines, Ticks, Grid, Color, Linewidth,
  * Marker, Markerfacecolor, Markeredgecolor, Markeredgewidth
  * Adding legends, labels to the plot
* Tight Layouting Images/ Padding the images,  Saving the images
* Other plotting libraries like seaborn and plotly

## 4. Pandas

* Install and check version of pandas

* How to import pandas?

* Series:
  * Creating Series
  * Accessing elements,
  * Indexing, Slicing,
  * Operations,
  * Missing values,
  * Sorting,
  * Statistics,
  * Applying functions,
  * Concatenating,
  * Filtering,
  * Grouping,
  * Merging,
  * Joining,
  * Reshaping,
  * Time series,
  * Plotting

* DataFrames:
  * Creating DataFrame,
  * Accessing elements,
  * Indexing,
  * Slicing,
  * Operations,
  * Missing values,
  * Sorting, Statistics,
  * Applying functions,
  * Concatenating,
  * Filtering,
  * Grouping,
  * Merging,
  * Joining,
  * Reshaping

* Reading csv files, creating csv files from DataFrames

* Groupby In Pandas:
  * Plotting in Pandas,
  * Missing values in Pandas,
  * Merging, Joining, Concatenating, and Reshaping DataFrames,
  * Time Series in Pandas,
  * Handling Missing values in Pandas,
  * Reading and Writing Files in Pandas

* Joins in Pandas: types of database join

* Loc and iLoc in Pandas:
  * Accessing elements in DataFrame,
  * Pivot Tables in Pandas,
  * Grouping and aggregating data

## 5. **Sympy**

* Introduction to Sympy
* importing Sympy
* Representing mathematical expressions
* Minor calculations using Sympy
* Plotting the equations and the solutions
* Derivatives In Sympy
  * Expressing in Sympy
  * Differentiation
  * Integration
  * Series expansion
  * Limit
  * Solving equations
      * Solving differential equations
      * Solving Initial Value Problems
      * Solving Higher Order Derivatives
      * Solving Partial Derivatives
* Integrals in Sympy
* Expressing the solution in Sympy
* Solving the integrals
* Solving Multiple integrals
