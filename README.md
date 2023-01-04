# ML-Project_8-info.-Customer-segmentation
### Data Details 

  Kaggle - https://www.kaggle.com/arjunbhasin2013/ccdata?select=CC+GENERAL.csv  
  Colab Notebook - https://colab.research.google.com/drive/1OlMkVJdrIi6BZMBJRSIab9pf5zpuN4YX?usp=sharing
  
#### Please use the Ipynb file in the repository for a detailed explanation of this project. This is because the project has been completed and the steps have been written in the notebook referenced in the repository.
Link - https://github.com/SudeepSinha09/ML-Project_8-info.-Customer-segmentation/blob/main/Customer%20segmentation.ipynb

## Description

This case requires to develop a customer segmentation to define marketing strategy.   
The sample Dataset summarizes the usage behavior of about 9000 active credit card holders during the last 6 months.  
The file is at a customer level with 18 behavioral variables.  

## An Overview of EDA

![image](https://user-images.githubusercontent.com/93086122/210520830-d63d333f-0fe6-4c50-9631-3782feeafb27.png)

## Attribute Information

Following is the Data Dictionary for Credit Card dataset :-

CUSTID : Identification of Credit Card holder (Categorical)  
BALANCE : Balance amount left in their account to make purchases  
BALANCEFREQUENCY : How frequently the Balance is updated, score between 0 and 1 (1 = frequently updated, 0 = not frequently updated)  
PURCHASES : Amount of purchases made from account  
ONEOFFPURCHASES : Maximum purchase amount done in one-go  
INSTALLMENTSPURCHASES : Amount of purchase done in installment  
CASHADVANCE : Cash in advance given by the user  
PURCHASESFREQUENCY : How frequently the Purchases are being made, score between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased)  
ONEOFFPURCHASESFREQUENCY : How frequently Purchases are happening in one-go (1 = frequently purchased, 0 = not frequently purchased)  
PURCHASESINSTALLMENTSFREQUENCY : How frequently purchases in installments are being done (1 = frequently done, 0 = not frequently done)   
CASHADVANCEFREQUENCY : How frequently the cash in advance being paid   
CASHADVANCETRX : Number of Transactions made with "Cash in Advanced"  
PURCHASESTRX : Numbe of purchase transactions made  
CREDITLIMIT : Limit of Credit Card for user  
PAYMENTS : Amount of Payment done by user  
MINIMUM_PAYMENTS : Minimum amount of payments made by user  
PRCFULLPAYMENT : Percent of full payment paid by user  
TENURE : Tenure of credit card service for user  

## Project Brief

In this project, we conducted a customer segmentation analysis to understand the different types of customers that a company has and to identify patterns in their behavior. The goal was to use this information to tailor marketing efforts and improve the customer experience.

To perform the customer segmentation analysis, we collected data on various characteristics of the customers, such as their demographics, purchasing habits, and preferences. We then cleaned and pre-processed the data to prepare it for modeling.

Next, we used the elbow method to find the optimal number of clusters for our customer segmentation analysis. This involved fitting a model with a range of different numbers of clusters and selecting the number of clusters that resulted in the most meaningful and distinct groupings of customers.

Finally, we used the identified number of clusters to build a cluster model and analyzed the resulting customer segments to gain insights and inform our marketing efforts. Overall, the project provided valuable insights into the diverse needs and preferences of our customers and helped us tailor our marketing efforts to better serve them.

#### The model selected - Finding the optimal number of clusters (Elbow)
