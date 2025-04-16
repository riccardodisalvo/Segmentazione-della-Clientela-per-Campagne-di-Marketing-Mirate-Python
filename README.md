# Customer Segmentation using K-Means Clustering 

## Overview

This project uses **K-Means clustering** to segment customers based on their purchasing behaviors and financial activity. By identifying customer groups, the company can design targeted marketing campaigns to enhance engagement and profitability. 

## Project Structure 

1. **Data Preprocessing**:
   - Cleaned and scaled the dataset for accurate model performance.
   - Handled missing values and outliers effectively.
   
2. **K-Means Clustering**:
   - Applied the **K-Means algorithm** to identify 4 clusters.
   - Evaluated clustering performance using the **Silhouette Score**.

3. **Cluster Analysis**:
   - Analyzed the clusters based on the average values of the original variables.
   - Visualized the clusters using **PCA** for a two-dimensional representation.

## Dataset 

The dataset includes various features that describe customer financial behavior. Below is a list of the key features used for clustering:

- **CUST_ID**: Customer's credit card ID (Categorical) 
- **BALANCE**: The remaining balance on the account 
- **BALANCE_FREQUENCY**: How often the balance is updated, ranging from 0 to 1 (1 = frequent, 0 = infrequent) 
- **PURCHASES**: Total amount spent by the customer 
- **ONEOFF_PURCHASES**: Maximum amount spent in a single purchase
- **INSTALLMENTS_PURCHASES**: Amount of purchases made in installments 
- **CASH_ADVANCE**: Cash advance taken by the customer 
- **PURCHASES_FREQUENCY**: Frequency of purchases, ranging from 0 to 1 (1 = frequent, 0 = infrequent) 
- **ONEOFFPURCHASESFREQUENCY**: Frequency of one-off purchases, ranging from 0 to 1 
- **PURCHASESINSTALLMENTSFREQUENCY**: Frequency of installment purchases, ranging from 0 to 1 
- **CASHADVANCEFREQUENCY**: Frequency of cash advances taken by the customer 
- **CASHADVANCETRX**: Number of cash advance transactions 
- **PURCHASES_TRX**: Number of purchase transactions completed 
- **CREDIT_LIMIT**: The credit limit of the cardholder 
- **PAYMENTS**: Total payments made by the customer 
- **MINIMUM_PAYMENTS**: Minimum amount paid by the customer 
- **PRCFULLPAYMENT**: Percentage of full payments made by the customer 
- **TENURE**: Duration of the customer’s credit card service 

The goal is to segment the current customer base into distinct clusters, each of which will receive targeted marketing campaigns from the company. 
