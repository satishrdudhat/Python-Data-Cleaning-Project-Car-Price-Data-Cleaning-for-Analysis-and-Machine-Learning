# Python-Data-Cleaning-Project-Car-Price-Data-Cleaning-for-Analysis-and-Machine-Learning
This project focuses on cleaning and preprocessing car price data for analysis and machine learning. It includes handling missing values, feature engineering, and exploratory data analysis (EDA).

# Car Price Data Cleaning for Data Analysis and Machine learning

# Features:
   •	Data Cleaning & Standardization
   •	Feature Engineering (Extracting car brands, price conversion)
   •	EDA & Machine Learning Preparation
 
# Tech Stack:
   •	Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
   
## Project Objective
The primary objective of this project is to clean and preprocess car price data to ensure accuracy and usability for further data analysis and machine learning applications. This includes handling missing values, feature engineering, and standardizing numerical fields.

## Dataset used
- <a href="https://github.com/satishrdudhat/Python-Data-Cleaning-Project-Car-Price-Data-Cleaning-for-Analysis-and-Machine-Learning/blob/main/car_price.csv">View Dataset</a>

## Key Performance Indicators (KPIs) & Questions

•	KPIs: 
   o	Percentage of missing values before and after cleaning
   o	Total number of records before and after preprocessing
   o	Standardization success rate for the car price column

•	Questions Addressed: 
   o	What are the major data quality issues in the dataset?
   o	How can car price values be converted into a uniform format?
   o	What transformations are necessary for effective analysis and modeling?

## Process of Data Cleaning

   Step 1: Data Loading & Initial Inspection
      •	Loaded dataset from car_price.csv
      •	Checked dataset shape and previewed initial records
      •	Identified data types of all columns
      
   Step 2: Handling Missing Values
      •	Counted missing values in each column
      •	Calculated missing value percentages
      •	Removed rows containing missing values
      •	Rechecked dataset for any remaining null values
      
   Step 3: Feature Engineering
      •	Extracted Car Company Name: 
             o	Derived the car manufacturer from the car_name column by splitting text
             o	Created a new column car_company_name
      •	Standardized Car Price Column: 
             o	Removed commas and formatted values
             o	Converted car prices expressed in 'Lakh' and 'Crore' to numerical values
             o	Ensured data type was set to float64

##  Data Analysis & Machine Learning Preparation

  •	Conducted exploratory data analysis (EDA) to identify trends and relationships
  •	Prepared cleaned data for machine learning by encoding categorical variables
  •	Normalized and scaled numerical data for better model performance
  •	Split dataset into training and testing sets for machine learning models

## Project Insights (Key Findings)

  •	The dataset initially contained missing values, which were successfully removed.
  •	The car_name column was split into car_company_name and car_name to enhance clarity.
  •	The car_prices_in_rupee column was converted into a standardized numerical format, enabling precise comparisons.
  •	The cleaned data is now suitable for advanced analytics and machine learning applications.

## All Data Cleaning.

Data Cleaning 1 : <br>
![Code 1](https://github.com/user-attachments/assets/5b3f4c40-bb2a-43f2-ad5e-7bcb9d93dc6f)

Data Cleaning 2 : <br>
![Code 2](https://github.com/user-attachments/assets/36085b72-865f-4ce4-9aa9-26b736a2a0d0)

Data Cleaning 3 : <br>
![Code 3](https://github.com/user-attachments/assets/20e0c787-9b72-4db8-9c02-d42d160c39f9)

Data Cleaning 4 : <br>
![Code 4](https://github.com/user-attachments/assets/bd2b56a3-7ab1-4834-99c5-a77fa6db80d3)

Data Cleaning 5: <br>
![Code 5](https://github.com/user-attachments/assets/c3e25d2a-0a7f-47d7-923d-1c2b5e66c518)

Data Cleaning 6: <br>
![Code 6](https://github.com/user-attachments/assets/55a60795-35a0-4351-85b6-060f2dd19280)

Data Cleaning 7: <br>
![Code 7](https://github.com/user-attachments/assets/b8854569-3105-4617-a328-a5f28aea62a2)

Data Cleaning 8: <br>
![Code 8](https://github.com/user-attachments/assets/98e2969d-c7f4-4c18-8ade-9651fdc2e7dc)

Data Cleaning 9: <br>
![Code 9](https://github.com/user-attachments/assets/837ff8cb-b140-408b-8af6-dd7db04ceaa2)

Data Cleaning 10: <br>
![Code 10](https://github.com/user-attachments/assets/c3e49c68-294e-4a95-b559-7844fa270a3b)

## Final Conclusion & Recommendations

 •	The dataset is now clean and ready for further data analysis and predictive modeling.
 •	Future improvements could include handling outliers in pricing, normalizing additional features, and enriching the dataset with external sources.
 •	Applying machine learning models such as regression and classification can help derive deeper insights from the dataset.

This cleaning process ensures the dataset is structured optimally for deeper insights and predictive modeling.
