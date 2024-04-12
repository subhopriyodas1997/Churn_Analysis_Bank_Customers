
# Churn Analysis 

<> Conducted a churn analysis using a dataset from Kaggle for a random bank, with the goal of uncovering insights to inform strategic decision-making. 

<> I diligently cleaned and transformed the data using Power Query Editor, ensuring its readiness for analysis and reporting. 

<> My focus was on organizing and modeling the data meticulously to identify key factors influencing customer churn. 

<> By leveraging these insights, I aimed to optimize our customer retention strategies and drive business growth.

## Links

 - [Live dashboard](https://github.com/matiassingers/awesome-readme)
 - [Data taken from Kaggle](https://www.kaggle.com/datasets)

## Problem Statement

The task revolved around churn analysis for bank customers. The data collected needed cleaning and transformation using Power Query Editor. Afterward, organizing and modeling the data was necessary for analysis and reporting. Insights derived from the analysis would guide decision-making processes within the bank.
## Task

<> Data collection and preparation

<> Data Modelling.

<> Created measures using DAX.

<> Created reports using the measures created and other data provided.
## Data collection and Preparation

- Assigned 1st row values as column headers.
- Renamed columns.
- Removed unnecessary columns.
- Changed the type of values from strings to integers or integers to text as needed.
- Created new columns from previous columns.
- Edited values in rows using the "Replace Values" function.
- Converted values like "0" and "1" from integer to string.
- Arranged "Credit Card Status", "Activity Status", and "Churn Status" columns.
- Categorically arranged individual ages using age groups.
- Similarly arranged the "Credit Score" and "Balance" columns and changed their data type from integer to string.
- Used the "Reference" function to create new tables for "Age Groups", "Credit Score", and "Account Balance" in ascending order with unique values.

## Data Modelling

Applied star schema to arrange the tables.
![Screenshot 2024-04-12 205451](https://github.com/subhopriyodas1997/Churn_Analysis_PowerBI/assets/120428930/6cb27810-70cb-4eeb-8e73-15d28225458d)

## Created measures

- Utilized DAX to create columns for metrics such as the number of customers (count of customer IDs), count of churned customers, and churn rate.
- Created custom columns for minimum, maximum, and target churn rates to be used in visualizations such as gauges.
- Developed visualizations including donuts, gauges, line charts, and line & clustered column charts.
- Added a slicer for "Churn Status" to facilitate interactive analysis.

## Dashboard Design
![Screenshot 2024-04-12 192358](https://github.com/subhopriyodas1997/Churn_Analysis_PowerBI/assets/120428930/c7efc7d1-3eb7-4c51-88aa-c53a92bc851c)


## Findings

<> Churn rate was consistently highest for the age group 51-60 years and for customers with a credit score <= 400.

<> Products 4 and 3 exhibited noticeably higher churn rates.

<> Germany had a noticeably higher churn rate for the account balance group 100k - 200k.
