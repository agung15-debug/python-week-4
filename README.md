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

   * head() function
  
     This function returns the first n rows for the object based on position. It is useful for quickly testing if your object has the right type of data in it.
   
   * info() function
   
     This function can see the column name, the number of Non-Null values and the type of data in each column in the 'Titanic' data.
   
   * notnull().sum() function
   
     This function to see the amount of data filled in from each column.
     
   * isnull().sum() function
     
     This function to see the empty value of each Titanic data column.
    
   * sum() function

     This function counts up all the data in each column.
     
   * tail() function
   
     This function to see the entire contents of the Titanic data starts from the bottom to the top.
     
   * shape() function
   
     Shape function to see the count of rows and columns in the data (row, column)
     
   * column() function
   
     Column function to see the column names in the data.
     
   * index() function
   
     Index function to see the count of rows in the data.
     
   * describe() function
   
     Describe the function to see statistics from each column in the data. Statistics include count, mean, std, min, and max.
     
   * mean() and median() function
   
     Mean and median functions to see the average and central value of data.
     
   * unique() function
   
     Unique function to see the unique value (different value) of data.
     
   * value_counts() function

     This function to see the amount of each unique value in the data.
  
