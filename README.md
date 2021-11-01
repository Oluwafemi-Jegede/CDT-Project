# Last Mile Delivery: Optimizing  Customer Delivery Time 

With the surge in e-commerce, there is a lot of pressure on logistic operations. The last mile is arguably the biggest problem in e-commerce as it addresses the question, “When will I receive my order?”. Last mile delivery is the most expensive and time consuming part of the shipping process. According to Mantoria inc,a logistics company, up to 30% of overall delivery costs can be incurred in that final stage of order fulfillment. So how does one reduce the cost and improve customer satisfaction by on time delivery?

# Contents

- Problem Statement
- The Data
- EDA


## Problem Statement

`“How might we optimize customer delivery time by predicting future orders from historical data (including both external and internal factors)?”`

We would like to build a model from historical orders and various derived features. The required features will be identified by an interactive process, from a broad range of available features in the data provided. The required range of features to be used for this project is divided in 3 broad categories:


- Customer:  This includes but not limited to, customer location, type of customer, type of apartment etc  
- Order: This includes order size, order weight,purchase date,approval date,   
- External Factors:  This includes mostly weather conditions; Rainfall and Temperature. Others are Holidays, traffic etc.

The above includes only measurable and predictable features, features such as sick drivers, accidents etc are not going to be included in our analysis.

## The Data

The data to be used is the Olist public data sets available on Kaggle. This dataset was generously provided by Olist, the largest department store in Brazilian marketplaces. Olist connects small businesses from all over Brazil to channels without hassle and with a single contract. Those merchants are able to sell their products through the Olist Store and ship them directly to the customers using Olist logistics partners.The dataset has information of 100k orders from 2016 to 2018 made at multiple marketplaces in Brazil. 

