# Understanding Product Properties That Can Help Predict Sales
Author: Robert Ramos

## Overview
The head of a retail chain has asked me to recommend strategies for determining what product characteristics lead to higher sales volume.

I focused on primarily on outlet sales as an indicator of how

## Variables 
Variables used in analysis

|Variable Name|Description   |   
|---|---|
|Item_Identifier|Unique product ID   | 
|Item_Weight |Weight of product| 
|Item_Fat_Content|Whether the product is low fat or regular
| Item_Visibility  |The percentage of total display area of all products in a - store allocated to the particular product  |
| Item_Type  |The category to which the product belongs| 
| Item_MRP  |Maximum Retail Price (list price) of the product   |   
| Outlet_identifier  |Unique store ID   |  
| Outlet_Establishment_Year  | The year in which store was established  |   
| Outlet_Size  | The size of the store in terms of ground area covered  |  
| Outlet_Location_Type  | The type of area in which the store is located  | 
| Outlet_Type  | Whether the outlet is a grocery store or some sort of supermarket  | 
|Item_Outlet_Sales   |  Sales of the product in the particular store. This is the target variable to be predicted|

## Methods
See my [Google Colab](https://colab.research.google.com/drive/1-nYMdKYLTlWY7F99ZTBCMHwFgM3eVi0F#scrollTo=gr63uFrBHyFm) for detailed steps I took to obtain, clean and analyze the data. The general steps were:
* Imported raw data from a csv file into a dataframe
* Cleaned data 
* 
