AIM
To study and implement dataset creation, loading, and basic dataset inspection in Python using the Pandas library.
______________________________________________________________________________________________________________________________

THEORY
Pandas is a powerful Python library used for handling structured data efficiently. It provides the DataFrame data structure, which stores data in tabular form with rows and columns. Datasets can be created manually using dictionaries or loaded from external CSV files. Pandas also provides built-in functions to inspect dataset size, dimensions, data types, statistical summaries, missing values, duplicates, and unique values. These operations are essential in data preprocessing and exploratory data analysis.

One-line explanation of functions used:

DataFrame() – Creates a tabular dataset from a dictionary or other structured data.

shape – Returns the number of rows and columns in the dataset.

size – Returns the total number of elements in the dataset.

info() – Displays column names, data types, and non-null values.

describe() – Provides statistical summary of numerical columns.

read_csv() – Loads a dataset from a CSV file into a DataFrame.

head() – Displays the first few rows of the dataset.

tail() – Displays the last few rows of the dataset.

sample() – Displays random rows from the dataset.

columns – Returns the names of all columns in the dataset.

isnull() – Checks for missing values in the dataset.

sum() – Adds the values, commonly used to count missing or duplicate entries.

duplicated() – Identifies duplicate rows in the dataset.

nunique() – Returns the number of unique values in each column.

______________________________________________________________________________________________________________________________

CONCLUSION
Thus, we successfully studied dataset creation, loading, and inspection using Pandas. We learned how to analyze dataset structure, summarize data statistically, and check for missing, duplicate, and unique values, which are important steps in data preprocessing and analysis.
