## Summary of Day 8 and 10 activities and insights

We learn about [Pandas](https://pandas.pydata.org/) - Pandas is a powerful library in Python for data manipulation and analysis.
<br>
In [Day 8 Notebook](../Day8_pandas_part1.ipynb) we cover 
1. [Importing Library](#importing-the-pandas-library)
2. [Loading Dataset](#loading-dataset)
3. [Basic Functions](#basic-functions)
4. [Checking Null Values](#checking-null-values)
5. [Handling Missing Values](#handling-missing-values)

While in [Day 10 Notebook](./Day10_pandas_part2,3.ipynb) we cover
1. **Unique Values**
   - unique(): Get unique values in a column.
   - nunique(): Get the count of unique values in a column.

2. **Group by**
   -   The groupby() function in Pandas is used to group a DataFrame by one or more columns and perform aggregation 

3. **Handling Categorical Data**
4. **Correlation**
5. **Visualizations**
Pandas integrates well with popular data visualization libraries like Matplotlib and Seaborn. Here are some examples:

   - **plot()**: Create various types of plots (line, bar, histogram, etc.).
   - **hist()**: Create a histogram.
   - **scatter()**: Create a scatter plot.
-------


1. #### Importing the Pandas library
    To import the Pandas library, use the following command:
    
    `import pandas as pd`


2. #### Loading Dataset

`df = pd.read_csv('data.csv') ` # Load data from CSV file


3. #### Basic Functions
- **head()**: Display the first few rows of the DataFrame.
- **tail()**: Display the last few rows of the DataFrame.
- **shape**: Get the number of rows and columns in the DataFrame.
- **info()**: Display summary information about the DataFrame.
-**describe()**: Generate descriptive statistics for the DataFrame.



4. #### Checking Null Values
- **isnull()**: Identify null values in the DataFrame.
-**isnull().sum()**: Get the count of null values in each column.

5. #### **Handling Missing Values**
There are several ways to handle missing values:

- **Imputation**: Replace missing values with mean, median, or mode.
  `df['column_name'].fillna(df['column_name'].mean(), inplace=True)`
  <br>
- **Deletion**: Remove rows or columns with missing values.
`df.dropna(inplace=True)`
<br> 
- **Placeholder** values: Replace missing values with a specific value (e.g., 'Unknown').
`df['column_name'].fillna('Unknown', inplace=True)`



