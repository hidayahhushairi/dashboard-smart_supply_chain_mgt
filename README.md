# Smart Supply Chain Management - Dashboard
![GitHub last commit (branch)](https://img.shields.io/github/last-commit/hidayahhushairi/dashboard-smart_supply_chain_mgt/main)

#### Dashboard Link: https://app.powerbi.com/view?r=eyJrIjoiODg5MWEwY2YtZTFmNC00MjE2LWJhMjQtMTU1YWZjYzQwOTg2IiwidCI6ImNkY2JiMGUyLTlmZWEtNGY1NC04NjcwLTY3MjcwNzc5N2FkYSIsImMiOjEwfQ%3D%3D

## About :
Smart supply chain management is an logistic organization that establishes manufacturing process, inventory, sales, and product distribution.
This dashboard is developed specifically for management, operational and customer service teams, suppliers and researchers. The objective to create this 
dashboard is to identify the risk factors that can impact the supply and demand integration and tackle business visibilty, cost, cybersecurity issues.

### Technologies Applied :
1.  Analytic Tool : Microsoft Power BI

### Problem Statement :
Supply chains have always been vulnerable to disruptions and has to adapt unforseen events. Due to its wide range of operations and international sales from retail outlets and sales agents across various continents, the organization had to encounter with complex system, where real-time business visibility are limited. The current system, blockchain technology has incompatible nodes towards new supply chain software, involving high energy consumption and consiquently had to deal with high maintenance cost and cybersecurity issue.

### Steps followed :
1.  Data Preparation : Obtained data source from Kaggle website 
                      (https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis?select=DataCoSupplyChainDataset.csv)
2.  Data Cleaning : Convert data types, resolve inconsistencies, remove outliers, and replace Spanish and blank values.
3.  Load : Transformed 180519 data is loaded into Microsoft Power BI.
4.  Data Modelling : Assigned relationship between three diferent categories (Sales and Agents | Order | Shipping)
5.  Design : Supply chain management business are break down into three categories, Sales, Order and Purchases.
4.  Data Implementation : Used DAX language to calculate measures.
   
![weeknum_measure](https://github.com/hidayahhushairi/dashboard-smart_supply_chain_mgt/assets/106440459/2d09d9e9-66d5-4bd0-9650-346f61050749)
![repeatorder_measure](https://github.com/hidayahhushairi/dashboard-smart_supply_chain_mgt/assets/106440459/a67ccb62-1862-412c-a6c6-04a6ab5680ea)
![transaction30days_measure](https://github.com/hidayahhushairi/dashboard-smart_supply_chain_mgt/assets/106440459/ea174095-6233-45fd-ae87-79f93822f7e8)

### Result :
Testing phase is conducted among 30 respondents that work in logistic industry to evaluate real-time metrics performance. The outcome of testing improves system modification.
(1) Functionality Testing : 96.7% of respondents satisfied with their experience using this dashboard.
(2) Usability Testing : 86.7% of respondents intriguued to suggest the dashboard to their department.

Achieved Reserch Objectives (1) : Discovered risk factors that supply chain management must be aware of.
-  Sales & Price of Inventory
-  Sales & Proffit
-  Sales & Delivery Status
-  Sales & Transaction Type, Shippingg Delivery Risk

Achieved Reserch Objectives (2) : Identified fraudulent suppliers buying pattern.
