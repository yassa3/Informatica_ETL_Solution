# **Informatica Project**

This project involves analyzing customer data from CSV files using Informatica. The aim is to extract and transform data to generate various reports and insights. Below are the steps and tasks accomplished by this project.

## **Project Overview**

The project performs the following tasks:

1. **Sum of Balances by Gender**: Calculate the total balance for male and female customers.
2. **Count of Active Customers by Gender**: Count the number of active male and female customers.
3. **Customer Age Group Distribution**: Group customers into age brackets and provide distribution statistics:
    - Age between 18 and 30
    - Age between 30 and 45
    - Age greater than 45
4. **Rank Customers by Balance**: Identify customers with a positive balance and rank them in ascending order.
5. **Top 5 Customers by Balance**: Extract all information for the top 5 customers with the highest balances.
6. **Credit Score Extremes**: Identify the highest and lowest credit scores among customers.

## **Files**

The project uses the following CSV files:

- **`Churn_Modelling2.csv`**
- **`Churn_Modelling3.csv`**

## **Outputs**

The project generates the following output files:

1. Sum of balances for male and female customers.
2. Number of active male and female customers.
3. Distribution of customers by age groups.
4. Ranked list of customers with positive balances.
5. Information for the top 5 customers by balance.
6. File with the highest and lowest credit score values.

## **Usage**

### **Prerequisites**

- Informatica PowerCenter or any other ETL tool compatible with the CSV format.

### **Steps**

1. **Load Data**: Import **`Churn_Modelling2.csv`** and **`Churn_Modelling3.csv`** into your ETL tool.
2. **Transform Data**: Apply transformations to:
    - Calculate the sum of balances by gender.
    - Count active customers by gender.
    - Group customers by age.
    - Rank customers with a positive balance.
    - Extract information for top 5 customers by balance.
    - Find the highest and lowest credit scores.
3. **Generate Output Files**: Configure your ETL tool to output the results into specified formats (CSV, Excel, etc.).
