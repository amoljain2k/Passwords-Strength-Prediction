Libraries/ Modules Used:

Importing Data and Data Analysis : Pandas
Import data from sql file : sqlite3
To perform numerical computation : numpy
For Data Visualization : matplotlib, seaborn, plotly
For error handling : warnings 
To get special character : string
For Model Buliding and to perform TF-IDF :scikit-learn
Collections counter


Steps performed in this project

Data Collection
Imported sql data using sqlite3 library and then used pd.read_sql_query() function to convert sql data into pandas dataframe

Data Cleaning
Removed irrevelant coloumn, checked for dupliate rows and missing values.

Data Analysis
Performed semantic analysis to make meaning conculsions from the data. i.e. natural language. Determined the count of password having only alphabets, only numbers, alphanumeric and having special characters.

Feature Engineering
Found factors which may effect the strength of the password. Lowercase charcter frequncy, Uppercase character frequency, Digit frequency and special case frequncy.

Data Analysis on new Features created
Performed descriptive analysis using boxplot and numerical computation such as max, min, mean, meadian to determine whether Total Length, Lowercase charcter frequncy,Uppercase character frequency, Digit frequency and Special case frequncy have effect on the password strength. We found out that length and Lowercase charcter frequncy have the most impact in password strength.

Feature Engineering
Performed univariate anlysis to find the set of features usefull for our ML Algorithm. Made use of Violin Plot and Distribution Plot to perform this task. Used TF-IDF(Term Frequency- Iverse Document Frequncy) to convert sting data into numerical format

Model Building
We have 1 dependent feature i.e, strength and 3 independent features i.e., password, length and Lowercase charcter frequncy. To train the model we use Logistic Regerssion.



