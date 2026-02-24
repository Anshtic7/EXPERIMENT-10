NAME: ANSH PRATAP SINGH

PRN: 25070123143

AIM: STUDY OF PANDAS LIBRARY

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
THEORY: 

Pandas is an open-source Python library used for data analysis, data manipulation, and data cleaning. It is built on top of NumPy and is widely used in data science, machine learning, statistics, and research work.

Pandas is mainly used for:

--->Handling structured data (tables, spreadsheets)

--->Data cleaning and preprocessing

--->Statistical analysis

--->Time series analysis

--->Reading and writing data from different file formats

df = pd.DataFrame(data) it is used to create a DataFrame object using the pandas library in Python.

df.shape is an attribute that returns a tuple representing

df.ndim stands for number of dimensions. It returns the total number of axes (dimensions) of the object.

df.size returns the total number of elements in the DataFrame.

df.columns is an attribute of a DataFrame that returns the column names (labels) of the DataFrame. It does not return the data inside the columns. It only returns the names of the columns.

df.dtypes is an attribute of a DataFrame that returns the data type (datatype) of each column and it tells us: what kind of values each column stores (integer, float, string, boolean, etc.).

df["MARKS"] is used to select a specific column from the DataFrame.

-->df → DataFrame object

-->"MARKS" → Column label (must match exactly, including case)

It returns the column as a Series object.

df.loc is a label-based indexing method in Pandas.

It is used to:

--->Select rows by their index label

--->Select columns by their column name

--->Access specific cells (row + column intersection).

df.iloc stands for Integer Location.

It is a position-based indexing method used to select data from a DataFrame using:

--->Row number (integer position)

--->Column number (integer position)

--->It does not use labels, it uses numerical positions.

(del) is a Python keyword used to delete objects or elements.

It can delete:

Variables,
List elements,
Dictionary keys,
Object attributes,
DataFrame columns.

[.mean()] it is a built-in statistical function in Pandas.Calculates the average of numeric values in that Series.

[.max()] it is a built-in statistical function in Pandas. It gives the largest numberic value in the series.

[.min()] it is a built-in statistical function in Pandas. It gives the smallest numberic value in the series.

---------------------------------------------------------------------------------------------

CONCLUSION: In this experiment, the basic operations of the pandas library were performed successfully. A DataFrame was created and its structural properties such as shape, dimensions, and size were analyzed. Various methods were used to access and manipulate data using .loc, .iloc, and column selection techniques. Statistical functions like mean were applied to perform basic data analysis. Column deletion and datatype inspection were also carried out. Overall, the experiment improved understanding of DataFrame handling and data manipulation in Python.
