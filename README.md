**PANDAS INTERVIEW QUESTIONS	**

    1. What is Pandas?
         ✍Pandas is a Python library used for working with data sets. It has functions for analyzing, cleaning, exploring, and manipulating data.
         ✍pandas is a Python package providing fast, flexible, and expressive data structures designed to make working with “relational” or “labeled” data both                easy and intuitive. It aims to be the fundamental high-level building block for doing practical, real-world data analysis in Python.
    2. What is Python pandas used for?
         ✍Pandas is an open source Python package that is most widely used for data science/data analysis and machine learning tasks. It is built on top of another            package named Numpy, which provides support for multi-dimensional arrays
      ❓WHERE ITS USED:Pandas is mainly used for data analysis and associated manipulation of tabular data in DataFrames. Pandas allows importing data from various        file formats such as comma-separated values, JSON, Parquet, SQL database tables or queries, and Microsoft Excel.
    3.What is a Series in Pandas?
    ✍ A Pandas Series is like a column in a table. It is a one-dimensional array holding data of any type.
      ❓HOW DO U WRITE PANDAS SERIES: You can create a series by calling pandas. Series() . An list, numpy array, dict can be turned into a pandas series. You should       use the simplest data structure that meets your needs.
    4. Mention the different Types of Data structures in pandas??
     🎁SERIES:
         ✍Pandas is a one-dimensional labeled array and capable of holding data of any type (integer, string, float, python objects, etc.)
         ✍Syntax: pandas.Series(data=None, index=None, dtype=None, name=None, copy=False, fastpath=False)
     🎁PARAMETERS:
         👉data: array- Contains data stored in Series.
         👉index: array-like or Index (1d)
         👉dtype: str, numpy.dtype, or ExtensionDtype, optional
         👉name: str, optional
         👉copy: bool, default False
     🎁DATAFRAME:  
    ✍ Pandas DataFrame is a two-dimensional size-mutable, potentially heterogeneous tabular data structure with labeled axes (rows and columns). A Data frame is a        two-dimensional data structure, i.e., data is aligned in a tabular fashion in rows and columns like a spreadsheet or SQL table, or a dict of Series objects.        Pandas DataFrame consists of three principal components, the data, rows, and columns.
     🎁CREATING A PANDAS DATAFRAME:
    ✍ In the real world, a Pandas DataFrame will be created by loading the datasets from existing storage, storage can be SQL Database, CSV file, and Excel file.           Pandas DataFrame can be created from the lists, dictionary, and from a list of dictionary etc. Dataframe can be created in different ways here are some ways         by which we create a dataframe:
    5. Explain Reindexing in pandas?
    ✍ Reindexing in Pandas can be used to change the index of rows and columns of a DataFrame. Indexes can be used with reference to many index DataStructure              associated with several pandas series or pandas DataFrame. Let’s see how can we Reindex the columns and rows in Pandas DataFrame. 
     🎁REINDEXING THE ROWS:
        👉One can reindex a single row or multiple rows by using reindex() method. Default values in the new index that are not present in the dataframe are                   assigned NaN.
        REINDEXING THE COLUMNS USING AXIS KEYWORD:
        👉One can reindex a single column or multiple columns by using reindex() method and by specifying the axis we want to reindex. Default values in the new               index that are not present in the dataframe are assigned NaN.
        REPLACING THE MISSING VALUES:
        👉Missing values from the dataframe can be filled by passing a value to the keyword fill_value. This keyword replaces the NaN values. 
    6. What are the key features of pandas library ?
     🎁15 PYTHON PANDAS FEATURES:
        👉Handling of data. The Pandas library provides a really fast and efficient way to manage and explore data
        👉Alignment and indexing
        👉Handling missing data
        👉Cleaning up data
        👉Input and output tools
        👉Multiple file formats supported
        👉Merging and joining of datasets
        👉A lot of time series
        👉Optimized performance
        👉Python support
        👉Visualize
        👉Grouping
        👉Mask Data
        👉Unique Data
        👉Perform mathematical operation on the Data
    7. What is pandas Used For ? 
    ✍Pandas is mainly used for data analysis and associated manipulation of tabular data in DataFrames. Pandas allows importing data from various file formats such       as comma-separated values, JSON, Parquet, SQL database tables or queries, and Microsoft Excel.
    8. How can we create copy of series in Pandas?
    ✍copy() method is used to create a copy of a series object's indices and its data (values). And it returns a copied series object as a result. The copy()              method has one parameter which is “deep”. The default value for this deep parameter is True.
    9. What is Time Series in pandas?
        👉Create the series of date
        👉Work with data timestamp
        👉Convert string data to timestamp
        👉Slicing of data using timestamp
        👉Resample your time series for different time period aggregates/summary statistics
        👉Working with missing data
    10. Explain Categorical Data in Pandas?
        ✍Categorical are a Pandas data type. A string variable consisting of only a few different values. Converting such a string variable to a categorical                 variable will save some memory. The lexical order of a variable is not the same as the logical order (“one”, “two”, “three”).
        ❓HOW DO PANDAS HANDLED CATEGORICAL DATA:
            ✍The basic strategy is to convert each category value into a new column and assign a 1 or 0 (True/False) value to the column. This has the benefit of                  not weighting a value improperly. There are many libraries out there that support one-hot encoding but the simplest one is using pandas ' .                          get_dummies() method.
    11. How will you create a series from dict in Python?
         ✍A Series is a one-dimensional labeled array capable of holding any data type (integers, strings, floating point numbers, Python objects, etc.). It has               to be remembered that unlike Python lists, a Series will always contain data of the same type.   
         ✍By using series methods using with index parameter and without using index parameter.
    12. What are operations on Series in pandas?
         👉Creating a Series
             ✍In the real world, a Pandas Series will be created by loading the datasets from existing storage, storage can be SQL Database, CSV file, and Excel                  file. Pandas Series can be created from the lists, dictionary, and from a scalar value etc. Series can be created in different ways, here are some                  ways by which we create a series:
         👉Accessing element of Series
               There are two ways through which we can access element of series, they are :
                    👉Accessing Element from Series with Position
                        ✍In order to access the series element refers to the index number. Use the index operator [ ] to access an element in a series. The index                             must be an integer. In order to access multiple elements from a series, we use Slice operation.
                    👉Accessing Element Using Label (index)
         👉Indexing and Selecting Data in Series
             ✍Indexing in pandas means simply selecting particular data from a Series. Indexing could mean selecting all the data, some of the data from particular               columns. Indexing can also be known as Subset Selection.
             🎁Indexing a Series using indexing operator [] :
                  Indexing operator is used to refer to the square brackets following an object. The .loc and .iloc indexers also use the indexing operator to make                   selections. In this indexing operator to refer to df[ ].
         👉Binary operation on Series
         👉Conversion Operation on Series
    13. What is a DataFrame in pandas?
    14. What are the different ways in which a DataFrame can be created in Pandas?
    15. How will you create an empty DataFrame in pandas?
    16. How will you add a column to a pandas DataFrame?
    17. How will you retrieve a single column from pandas DataFrame?
    18. range ()  vs and xrange () functions in Python?
    19. What is the name of pandas library tools used to create a scatter plot matrix?
    20. What is pylab?
    21. Define the different ways a DataFrame can be created in pandas?
    22. Explain Categorical data in Pandas?
    23. How will you create a series from dict in Pandas?
    24. How can we create a copy of the series in Pandas?
    25. How will you create an empty DataFrame in Pandas?
    26. How will you add a column to a pandas DataFrame?
    27. How to add an Index, row, or column to a Pandas DataFrame?
    28. How to Delete Indices, Rows or Columns From a Pandas Data Frame?
    29. How to Rename the Index or Columns of a Pandas DataFrame?
    30. How to iterate over a Pandas DataFrame?
    31. How to get the items of series A not present in series B?
    32. How to get the items not common to both series A and series B?
    33. How to get the minimum, 25th percentile, median, 75th, and max of a numeric series?
    34. How to get frequency counts of unique items of a series?
    35. How to convert a numpy array to a dataframe of given shape?
    36. How can we convert a Series to DataFrame?
    37. How can we sort the DataFrame?
    38. How to convert String to date?
    39. What is Data Aggregation? 
    40. What is Pandas Index?
    41. Define ReIndexing?
    42. Define Multiple Indexing?
    43. How to Set the index?
    44. How to Reset the index?
    45. Describe Data Operations in Pandas?
    46. Define GroupBy in Pandas?
    47. How will you append new rows to a pandas DataFrame?
    48. How will you delete rows from a pandas DataFrame?
    49. How will you get the number of rows and columns of a DataFrame in pandas?
    50. What is Pandas ml?
    51. What is Pandas Charm?
    52. How will you add a scalar column with same value for all rows to a pandas DataFrame?
    53. How can we select a column in pandas DataFrame?
    54. How can we retrieve a row in pandas DataFrame ?
    55. How will you convert a DataFrame to an array in pandas?
    56. How can you check if a DataFrame is empty in pandas?
    57. How can you get the sum of values of a column in pandas DataFrame?
    58. How will you get the average of values of a column in pandas DataFrame?
    59. How will you apply a function to every data element in a DataFrame
    60. How will you get the top 2 rows from a DataFrame in pandas?
    61. List major features of the Python pandas?
    62. Enlist different types of Data Structures available in Pandas?
    63. How To Write a Pandas DataFrame to a File
    64. When, Why And How You Should Reshape Your Pandas DataFrame
    65. Does Pandas Recognize Dates When Importing Data?
    66. How To Format The Data in Your Pandas DataFrame?
    67. How To Add an Index, Row or Column to a Pandas DataFrame?
    68. How To Select an Index or Column From a Pandas DataFrame?
    69. How will you get the average of values of a column in pandas DataFrame?
    70. How to Apply function to every row in a Pandas Data Frame?
    71. What is use of GroupBy objects in Pandas?
    72. What is Pandas NumPy?
    73. What is Vectorization in Python pandas?
    74. List some alternatives of Python Pandas?
    75. How to convert a Data Frame to an array in Pandas?
    76. List some statistical functions in Python Pandas?
    77. Explain Series In pandas. How To Create Copy of Series In pandas?
    78. What Are the Different Ways A DataFrame Can Be Created In pandas?
    79. Difference between shallow copy and deep copy?
       🎁SHALLOW COPY:
           👉It is the copy of the collection structure, not the elements.	It is the copy of the collections with all 
           👉Affects the initial series.
           👉Shallow copy doesn’t replicate child objects.
           👉Creating a shallow copy is fast as compared to a deep copy.
           👉The copy is dependent on the original
       🎁DEEP COPY:
           👉It is the copy of the collections with all the elements in the original collection duplicated.
           👉Does not affect the initial series.
           👉Deep copy replicates child objects recursively.
           👉Creating a deep copy is slow as compared to a shallow copy.
           👉The copy is not fully dependent on the original.
    
 
