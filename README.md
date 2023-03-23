# EDA-BIG-MART-SALES

This repository contains an exploratory data analysis (EDA) of the BigMart Sales Dataset. The dataset contains sales data for a number of products sold at various BigMart stores. The aim of this analysis is to gain insights into the data, identify any trends or patterns, and provide a basis for further analysis.

## Dataset

The dataset used in this analysis is the BigMart Sales Dataset, which can be downloaded from Kaggle[https://www.kaggle.com/datasets/akashdeepkuila/big-mart-sales]. The dataset contains sales data for 1559 products across 10 stores of year 2013. The dataset includes information on the product, store, and sales, as well as other relevant features such as weight, visibility, and type of outlet.

## Dataset Details

The dataset has 8523 rows of 12 variables.

### Variable - Details

* Item_Identifier- Unique product ID
* Item_Weight- Weight of product
* Item_Fat_Content - Whether the product is low fat or not
* Item_Visibility - The % of total display area of all products in a store allocated to the particular product
* Item_Type - The category to which the product belongs
* Item_MRP - Maximum Retail Price (list price) of the product
* Outlet_Identifier - Unique store ID
* Outlet_Establishment_Year- The year in which store was established
* Outlet_Size - The size of the store in terms of ground area covered
* Outlet_Location_Type- The type of city in which the store is located
* Outlet_Type- Whether the outlet is just a grocery store or some sort of supermarket
* Item_Outlet_Sales - Sales of the product in the particulat store. This is the outcome variable to be predicted.

## Requirements

The analysis was performed using Python 3.3 and the following Python packages:

pandas
numpy
matplotlib
seaborn
These packages can be installed using pip.

## Files

EDA_BigMart_Sales.ipynb: Jupyter notebook containing the analysis
BigMartSales.csv: CSV file containing the dataset used in the analysis
README.md: This file in which all the information related to the project is given

## Analysis

The analysis begins with an overview of the dataset, including the number of observations and variables, as well as a summary of the data types and any missing values. The data is then explored in more detail, with visualizations and summary statistics used to identify any patterns or trends in the data. This includes exploring the relationship between sales and various product and store features, as well as examining the distribution of sales across different categories.

## Conclusion

After doing all the steps and doing necessary check, we saw that `MRP` is highly correlated with sales. With the help of this I have made an assumption that people are thinking ig the MRP is high then their quality of product it is good. So, to increase the sales we can look for the product whose price is too low so that it can also contribute to the sales of store.
