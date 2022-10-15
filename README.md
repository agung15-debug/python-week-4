# Python-Week-4
**1. Pandas**

Pandas is a library in Python that provides easy-to-use data structures and data analysis. Pandas is commonly used to create tables, change data dimensions, check data, and so on. The basic data structure in Pandas is called DataFrame, which makes it easy for us to read a file with many types of formats such as .txt, .csv, and .tsv files. This feature will make it a table and can also process data using operations such as join, distinct, group by, aggregation, and other techniques found in SQL.

- Data Series

   Pandas Series is a one-dimensional labeled array capable of holding data of any type (integer, string, float, python objects, etc.). The axis labels are collectively   called index.
 
 - loc and iloc
   * loc is label-based, which means that you have to specify rows and columns based on their row and column labels
   * iloc is integer position-based, so you have to specify rows and columns by their integer position values (0-based integer position)

- Data Frame

   A Pandas DataFrame is a 2 dimensional data structure, like a 2 dimensional array, or a table with rows and columns.

   * Pandas import csv file

     The pandas function read_csv() reads in values, where the delimiter is a comma character. You can export a file into a csv file in any modern office suite including Google Sheets

   * head()function
  
     This function returns the first n rows for the object based on position. It is useful for quickly testing if your object has the right type of data in it.
