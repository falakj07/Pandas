# Experiment No. 9


## Name - Falak Jain 
## PRN - 25070123047
## Batch - ENTC A3



# Title - Study of Pandas 


## Aim :
To study and understand the Pandas library in Python and perform   analysis operations such as creating Series and DataFrames, importing datasets, cleaning data, and applying statistical functions.


## Theory : 

Pandas is an open-source Python library used for data manipulation, data analysis, and data cleaning. Pandas is widely used in data science, machine learning, and data analytics projects.

**1**. **Key Data Structures in Pandas**

****a) Series :**** 
A Series is a one-dimensional labeled array capable of holding data of any type (integers, strings, floats, etc.). Each element in a Series has an index.

Example:

import pandas as pd

s = pd.Series([10, 20, 30]).

****b) DataFrame****-
A DataFrame is a two-dimensional labeled data structure with rows and columns, similar to a table in a database or an Excel spreadsheet.A DataFrame can store data of different types such as integers, floats, strings, and more. It is one of the most important and widely used data structures in data analysis.

Example:

data = {'Name': ['A', 'B'], 'Marks': [85, 90]}
df = pd.DataFrame(data)

****c) Structure of Dataframe**** 

*****A)Viewing Basic Structure*****

1)df.info()-
This function provides a complete summary of the DataFrame structure:
Number of rows and columns
Column names
Data types of each column
Number of non-null values

2)df.shape-
Returns the number of rows and columns in tuple form:
Output example:
(100, 5)

3)df.columns-
Shows the names of all columns.

4)df.index-
Displays the row index (labels).

5)df.size-
returns the total number of elements in the DataFrame.


6)df.ndim-
df.ndim is used to find the number of dimensions (axes) of a DataFrame.


*****B)Checking Data Types*****

a) df.dtypes-
Shows the data type of each column.

Common data types:
int64
float64
object (usually string)
bool

*****C)Viewing Sample Data*****

a) df.head()-
Shows first 5 rows (default).

b)df.tail()-
Shows last 5 rows.These help in visually understanding the structure of data.


*****D) Descriptive Structure Information*****

a)df.describe()

Provides statistical summary of numerical columns:
Count
Mean
Standard deviation
Minimum and maximum values

*****E) Checking Missing Values*****

a)df.isnull().sum()

Understanding structure also includes checking null values.

b)df.isna-
The function df.isna() is used to detect missing (null) values in a DataFrame.

df.isna() -  returns a DataFrame of Boolean values:

True → if the value is missing (NaN / None)

False → if the value is not missing

c)df.drop

df.drop() is used to remove rows or columns from a DataFrame.

It does not modify the original DataFrame unless we use inplace=True.

## Conclusion :

In this experiment, we studied the DataFrame in Pandas and learned how to create and analyze tabular data. We understood important properties like shape, size, and dimensions. DataFrame makes data handling easy and efficient in Python.




















