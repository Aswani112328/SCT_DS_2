Titanic Data Analysis & Exploratory Data Analysis (EDA)

This project explores the Titanic dataset to identify patterns and factors that influenced passenger survival rates. Using Python's data science ecosystem, the analysis delves into demographics (age, sex), socio-economic status (class), and other variables to visualize the story behind the disaster.

📊 Project Overview

The goal of this project is to perform a comprehensive EDA to understand the relationship between passenger features and their survival probability.

Key questions addressed:

Did gender play a significant role in survival?

How did passenger class affect the chances of making it to a lifeboat?

What was the age distribution of survivors versus non-survivors?

Did traveling with family (SibSp/Parch) increase or decrease survival odds?

📁 Repository Structure

task2.ipynb: The main Jupyter Notebook containing the data cleaning, analysis, and visualizations.

train.csv: The raw dataset containing passenger information (Name, Age, Sex, Ticket Class, etc.).

🛠️ Technologies Used

Python 3

Pandas: For data manipulation and cleaning.

NumPy: For numerical operations.

Matplotlib & Seaborn: For creating insightful static visualizations (histograms, bar charts, heatmaps).

📈 Key Insights from the Analysis

Gender: Female passengers had a significantly higher survival rate compared to males, reflecting the "women and children first" policy.

Socio-economic Status: Passengers in 1st Class had the highest survival rate, while those in 3rd Class faced the highest mortality rate.

Age: Younger children had better survival odds, while the majority of passengers were in the 20–40 age range.

Missing Data: Significant missing values were identified in the Age and Cabin columns, which required handling/imputation before analysis.
# SCT_DS_2
