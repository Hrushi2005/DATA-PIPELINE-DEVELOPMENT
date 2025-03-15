# DATA-PIPELINE-DEVELOPMENT
COMPANY: CODTECH IT SOLUTIONS

*NAME*: Y.HRUSHI VENKATA TRINADH

*INTERN ID*::CODHC233

*DOMAIN*: Data Science

*DURATION*: 6 WEEEKS

*MENTOR*: NEELA SANTOSH


This code processes the Titanic dataset by handling missing values. First, it reads the dataset using pandas. The numeric columns (X) and object (categorical) columns (y) are identified separately. A machine learning Pipeline with a SimpleImputer is created, using the "most_frequent" strategy, which replaces missing values with the most common value in each column.

The pipeline is then applied to both numeric (X) and categorical (y) columns of the dataset to fill missing data. Finally, the cleaned dataset is saved as a new CSV file named final.csv. This approach ensures that the dataset has no missing values, making it ready for further analysis or machine learning tasks.

*output*-final.csv file
