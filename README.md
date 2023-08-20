# Basic Data Manipulation using PySpark
This notebook demonstrates basic data manipulation techniques using PySpark, a powerful framework for distributed data processing. It covers several aspects of data manipulation, including data loading, null value handling, filtering, aggregation, and linear regression using PySpark.

## Section 1 - Basic Manipulation
### Data Loading
- The notebook begins by installing the required PySpark library using !pip install pyspark.
- It imports necessary libraries like pandas and pyspark, then reads a CSV file named 'age.csv' using both Pandas and PySpark.
- A SparkSession named 'Practise' is created and used to read the CSV file into a DataFrame named df_pyspark.
- Various operations are performed on the DataFrame, such as showing its content, displaying its schema, selecting specific columns, adding and removing columns, and renaming columns.

## Section 2 - Null Value Manipulation
### Null Value Handling
- This section demonstrates handling null values in a DataFrame.
- A CSV file named 'test2.csv' is read into a DataFrame named df.
- Different techniques are shown to drop rows with null values, set thresholds for dropping rows, and impute missing values using the Imputer function from PySpark's ml.feature module.
- Various filtering operations are also showcased, including filtering based on conditions using logical operators.

## Section 3 - Grouping, Aggregation, and Ranking
### Grouping, Aggregation, and Ranking
- The notebook introduces a new DataFrame df2 by reading a CSV file named 'test3.csv'.
- Grouping and aggregation operations are demonstrated using the groupBy, agg, and Window functions.
- The rank function from the window module is used to rank individuals within departments based on salary.
- Filtering operations are showcased based on rank and salary conditions.

## Section 4 - Linear Regression using PySpark's MLlib
### Linear Regression using MLlib
- The section focuses on using PySpark's MLlib to perform linear regression.
- The DataFrame df1 is used for training.
- Independent features are created using the VectorAssembler to group 'age' and 'Experience'.
- A linear regression model is trained, evaluated, and used for predictions.
- Evaluation metrics like mean absolute error and mean squared error are calculated.

This notebook provides a hands-on introduction to essential data manipulation techniques using PySpark. It covers data loading, cleaning, filtering, aggregation, and even basic machine learning tasks such as linear regression. Feel free to explore and modify the provided code snippets to suit your specific data manipulation needs.

## Credits
The content and code in this notebook are adapted from the tutorials and materials provided by Krish Naik.
