# bank-loan
Title: Logistic Regression Analysis for Loan Approval Decision 

The dataset contained information on bank customers of those who accepted a personal loan and those who did not accept the loan. 
The aim is to build a model that can predict whether customers would take a loan or not. 
I used a Logistic regression algorithm to build a machine learning model to solve this problem since it can predict a binary class, i.e., Yes or no.

Data Assessment:
Immediately after reading data into jupyter notebook using pandas read_excel function, data need to be assessed to check its first few rows, data types, missing data, the shape of the data and have the description of data. 
This can tell us how clean and tidy the data is. The dataset has 5,000 rows and 14 columns, an output of the pandas' shape method. 
The dataset is missing since all columns have "5,000 non-null" values. All columns are in numeric data types, int64 and float64. 
umeric data types are readily usable for machine learning algorithms. Besides, I also checked for data duplication; no data duplication was there. 
Looked into a preview of the data using describe function; the function gives an overview of the dataset, for example, mean, median, max, min, std, 25% quantile, and 75% quantile for each numerical column in the dataset. 
Description of the dataset can tell us a lot about data.
