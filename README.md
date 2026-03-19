# Online-retail-e-commerce-sales-analysis
This project explores the online retail dataset which is based on uk e-commerce (transaction from both 2009-2010 and 2010-2011) to understand customer behaviour, product performance, and revenue drivers. It includes data cleaning, Featured engineering, EDA, and bussiness recommendations.

## Project Objective
* clean and preprocess messy retail transaction data
* convert data types, handling missing values, and remove invalid entries
* Engineer new features such as total revenue and monthly sales
* Perform exploratory data analysis (EDA) to identify trends and patterns
* Generate insights relevent to retail and e-commerce decision- making

  ## Data Cleaning and Preprocessing
  key step perdormed in the notebook:
  * Converting InvoiceData to datetime
  * Fixing numeric columns (quantity, price)
  * Handling missing CustomerID values
  * Removed cancelled or negative transactions
  * creating new fields such as : TotalPrice , InvoiceYear Month, RevenuePerInvoice
    The cleaned data is saved and included in the Data folder

    ## Exploratory Data Analysis (EDA)
  The analysis covers:
  * Monthly revenue trends
  * Top-selling products
  * customer purchasing patterns
  * Country-Level sales distribution
  * Revenue contribution by customer segments
    Visualisations are created by using Pandas, Matplotlib, and seaborn.

    ## Dataset information
Original dataset contain transcations from 2009-2010 and 2010-2011 for the comparison analysis. sample dataset containing  both 2009-2010 and 2010-2011 transactions (5030 rows with all original columns) has been uploaded because the full dataset exceeds GitHub's file size limits.  The original dataset can be downloaded from UCI Machine Learning Repository :  https://archive.ics.uci.edu/dataset/502/online+retail+ii

## Skills Demonstrated 
* Data cleaning and Wrangling
* Exploratory data analysis
* Feature engineering
* Data visualisation
* Insight generation
