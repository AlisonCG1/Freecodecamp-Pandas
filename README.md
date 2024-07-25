# Freecodecamp-Pandas


# Pandas

Pandas
Pandas is a powerful and widely used Python data manipulation and analysis library. It provides two primary data structures: Series and DataFrame.
Series
A Series is a one-dimensional array-like object containing an ordered sequence of elements with a specified index. While it looks similar to a Python list, there are key differences:
Homogeneous Data Type: A Series can only contain one type of data.
Name Attribute: Series can have an optional name.
Array-backed: Series are backed by NumPy arrays, providing efficient performance.
Flexible Indexing: Series indexes can be changed, allowing for the recall of values by name.
Ordered Dictionary: Series are like ordered dictionaries but maintain order.
Data Access: Series allows data access using .iloc[] for integer-location-based indexing and .loc[] for label-based indexing.
Multi-indexing: Series supports hierarchical indexing (multi-indexing).
Range Support: Series supports slicing and range operations.


## Important functions in Dataframes:

.shape tells us how many columns and rows we have in a dataset. 
.info gives us an understanding of the properties of the data we are about to work with. 
Size gives us the size of the dataframe 
.Index shows the index of the dataframe
.dtype shows data types
.describe tells us the statistical properties of the data.
.loc locates data in a row 
.iloc selects rows by sequential position 
.drop drops values, and columns selected 
.mean shows the average of the data
.log shows a log of the data
.std standard deviation 
~ NOT
|  OR
& AND


## DataFrame

A DataFrame is a two-dimensional, size-mutable, potentially heterogeneous tabular data structure with labeled axes (rows and columns). Key features include:
Column as Series: Each column in a DataFrame is a Series.
Flexible Indexing: DataFrames have row and column indexes that can be changed.
Data Handling: DataFrames allow for easy data merging, grouping, and reshaping.
Data Input/Output: Pandas can read and write data from various sources like databases, Excel files, CSV files, and APIs.
Primary Library: Pandas is crucial for data analysis and is often used in conjunction with machine learning libraries.



## Knowledge from: 

- [@FreeCodeCamp](https://www.freecodecamp.org/learn/data-analysis-with-python/#data-analysis-with-python-course)


## Libraries used: 

- [@Pandas](https://pandas.pydata.org/docs/)
