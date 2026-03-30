Here’s the same content without highlights or formatting emphasis:

---

Aim
To study the basics of the Pandas library in Python by creating and manipulating Series and DataFrames, and performing fundamental data operations.

---

Theory
Pandas is a powerful Python library used for data manipulation and analysis. It provides two primary data structures.

Series is a one-dimensional labeled array capable of holding any data type.
DataFrame is a two-dimensional labeled data structure like a table with rows and columns.

In this experiment, a Series is created to store numerical data. A DataFrame is created using a dictionary. Various attributes and methods are used to explore the structure of the data. Data is accessed, modified, and analyzed using indexing and built-in functions.

Pandas simplifies tasks like data cleaning, transformation, and analysis, making it widely used in data science.

---

Functions / Methods Used

pd.Series()
Creates a one-dimensional labeled array.
Example: pd.Series([1,3,5,6,8])

pd.DataFrame()
Creates a table-like structure from a dictionary or other data.
Example: pd.DataFrame(data)

df.shape
Returns the number of rows and columns.

df.ndim
Returns the number of dimensions.

df.size
Returns total number of elements in the DataFrame.

df.columns
Displays column names.

df.dtypes
Shows the data type of each column.

df["column_name"]
Accesses a specific column.

df.loc[]
Accesses data using labels.

df.iloc[]
Accesses data using index positions.

Column Assignment
Used to add a new column.
Example: df["Grade"] = [...]

Updating Values
Used to modify existing data using loc or iloc.

df.drop()
Removes a column or row.

max()
Finds maximum value in a column.

min()
Finds minimum value in a column.

---

Conclusion
This experiment demonstrates how Pandas can be used to efficiently create, access, and manipulate structured data. It highlights the importance of DataFrames in handling tabular data and shows how built-in functions simplify data analysis tasks.

---



