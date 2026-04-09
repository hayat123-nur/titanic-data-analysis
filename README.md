🚢 Titanic Data Analysis Project
📌 Overview

This project analyzes the Titanic dataset using Python (Pandas).
It includes data creation, cleaning, exploration, analysis, and insights.

📂 Project Structure
Task_3_Titanic_Analysis.ipynb → Main notebook
dataset-2.csv → Dataset (if included)
🧩 Part 1: Custom Dataset
Created a dataset using a Python dictionary
Contains:
5 columns
15 rows
Custom index
🚢 Part 2: Titanic Dataset
🔍 Data Exploration
.head() → View first rows
.info() → Data types and structure
.describe() → Statistical summary
🧹 Data Cleaning
Filled missing values:
Age → median
Embarked → mode
Dropped unnecessary column (Cabin if exists)
Removed duplicate rows
📊 Data Analysis

Used groupby() to analyze:

Survival rate by gender
Survival rate by passenger class
Average age per class
Survival rate by age group
🔎 Data Filtering
Female passengers who survived
Children who survived
First-class passengers who survived
📈 Key Insights
Females were more likely to survive than males
First-class passengers had higher survival rates
Children had better survival chances
Female passengers in first class had the highest survival rate
🛠️ Tools Used
Python
Pandas
Google Colab
🎯 Conclusion

This project demonstrates basic data analysis workflow:

Data creation
Data cleaning
Data exploration
Data analysis
Insight generation
