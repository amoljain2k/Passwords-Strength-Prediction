# Passwords-Strength-Prediction

## **Libraries/Modules Used:**

* **Pandas**: For importing data and data analysis.
* **Sqlite3**: To import data from SQL file.
* **Numpy**: To perform numerical computation.
* **Matplotlib, Seaborn, Plotly**: For data visualization.
* **Warnings**: For error handling.
* **String**: To get special characters.
* **Scikit-learn**: For model building and TF-IDF.

## **Steps performed in this project:**

1 Data Collection:
Imported SQL data using sqlite3 library and then used pd.read_sql_query() function to convert SQL data into a Pandas DataFrame.

2 Data Cleaning:
Removed irrelevant columns, checked for duplicate rows, and missing values.

3 Data Analysis:
Performed semantic analysis to draw meaningful conclusions from the data, i.e., natural language. Determined the count of passwords having only alphabets, only numbers, alphanumeric, and containing special characters.

4 Feature Engineering:
Identified factors that may affect the strength of the password: lowercase character frequency, uppercase character frequency, digit frequency, and special case frequency.

5 Data Analysis on New Features Created:
Conducted descriptive analysis using boxplots and numerical computations such as max, min, mean, and median to determine whether Total Length, Lowercase character frequency, Uppercase character frequency, Digit frequency, and Special case frequency have an effect on the password strength.

6 Feature Engineering (Continued):
Performed univariate analysis to find the set of features useful for our ML Algorithm. Utilized Violin Plot and Distribution Plot to perform this task. Employed TF-IDF (Term Frequency-Inverse Document Frequency) to convert string data into numerical format.

7 Model Building:
With 1 dependent feature (strength) and 3 independent features (password, length, and lowercase character frequency), trained the model using Logistic Regression.
