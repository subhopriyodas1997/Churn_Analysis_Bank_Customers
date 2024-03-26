# Churn_Analysis_Bank_Customers

#Step.1. Data Collection and Preparation: Connect to, clean and transform raw data using Power Query Editor.

#Assign 1st row values as column headers.
#Rename columns.
#Remove unnecessary columns.
#Change type of values from strings to integers or integers to text as needed. 
#Create new columns from previous columns. 
#Edit values in rows using "Replace Values" function. 
#Convert values like "0" and "1" from integer to string. Then using "Replace Values" function convert "0" in "Credit Card Status" column to "Not Owned" and "1" to "Owned". Then the count function can be used in the latter stages when dashboard is made. 
#We similarly arrange the "Activity Status" and "Churn Status" columns.
#Then we use age groups to categorically arrange the individual ages given. 
#We do the same for "credit score" and "Balance" columns because that column also has so many different values. Then we change data type of these conditional columns from integer to string. 

#Step.2. Data Modeling: Create queries to organize data for Analysis and Reporting.

#Used the "Reference" function to create a new table for "Age Groups" in ascending order. This new table has only the unique values from "Age Groups" and sorted in ascending order using index values 1 to 7.
#We do the same for "Credit Score" and "Account Balance".

#Step.3. Create Measures: We use DAX for this purpose. 

#We use DAX to ccreate columns that we then use to create cards such as Number of customers(by using count of customer IDs), and count of customers churned and then churn rate. 
#We also later use the "Transform Data" function again to create custom columns such as minimum , maximum and target churn rate so that we can use these to create a gauge. 
#We create donuts, a gauge and line and Line & Clustered column charts and we add a slicer for "Churn Status".

#Step.4. Conclusions.
#Other factors varying, the churn rate consistently seems to be the highest for age group 51-60 years and credit score<=400. 
#Prod 4 and Prod 3 have noticeably more churn rate. 
#Germany has noticeably more churn rate for account balance group 100k - 200k.

#Step.5. Enhance the report using themes. 
