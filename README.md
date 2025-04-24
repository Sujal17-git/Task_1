# Task-1
AI-ML Internship By Elevate Labs
i choose titanic dataset to perform all data preporosessing task
and to perform task i choose Jupiter Notebook 

Tools : Pandas, matplotlib.pyplot

1.Import the dataset and explore basic info (nulls, data types).
 - import it using pandas and name it 'Titanic_Dataset'
 - isnull().sum() used to calculate null values
 - and dypes() used to show Data types of Columns 

2.Handle missing values using mean/median/imputation.
 - fill missing values of Age column by its Mean
 - fill missing values of Cabin by 'Unknown' cause there are many (nearly 650) Missing values we can't replace it by Mean/median/mode and we cant remove all rows so optimal way is filling all values by Unknown
 - fill missing values of Embarked by its Mode(most repetative value)
   
3.Convert categorical features into numerical using encoding.
 - Add new column named Embarked_code and perform mapping like this -  embarked_mapping = {'S': 0, 'C': 1, 'Q': 2}
4.Normalize/standardize the numerical features.
 - Normalize/standardize 'Age' and 'Fare' column and add 4 columns Age_Normalize, Age_Standardize, Fare_Normalize, Fare_Standardize
   
5.Visualize outliers using boxplots and remove them
 - after importing matplotlib.pyplot i plot Box Plot and visualize outliers and remove it 
