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
(2) Usability Testing : 86.7% of respondents intrigued to suggest the dashboard to their department.

- Overview Page : <img width="943" height="529" alt="image" src="https://github.com/user-attachments/assets/1de9354c-4a36-47ed-ad02-920bc5791575" />
- Sales Page : <img width="931" height="521" alt="image" src="https://github.com/user-attachments/assets/33fb6329-ae15-40a0-adb0-e8ae02690f00" />
Sales Summary Analysis : <img width="936" height="523" alt="image" src="https://github.com/user-attachments/assets/75a88b34-e983-4b61-839a-d943148e4f08" />
Inventory Page : <img width="935" height="524" alt="image" src="https://github.com/user-attachments/assets/e32b8427-e699-4f35-b9df-6f9b829f6c88" />
Fraudulent Supplier Page : <img width="906" height="508" alt="image" src="https://github.com/user-attachments/assets/2826a5b5-86f7-41ec-8db6-130483a84e3c" />
Purchases Page : <img width="922" height="518" alt="image" src="https://github.com/user-attachments/assets/952823e6-6a48-4e9e-b38b-05055a310410" />

#### Achieved Reserch Objectives (1) : Discovered risk factors that supply chain management must be aware of.
-  Sales & Price of Inventory <br>
  <img width="593" height="283" alt="image" src="https://github.com/user-attachments/assets/1147b5e7-8b65-4752-b25c-ab6615784790" /> <br>


-  Sales & Profit <br>
  <img width="493" height="323" alt="image" src="https://github.com/user-attachments/assets/4d0838bb-479d-498e-af70-8378dfc7cd7d" /> <br>
The line chart above reveals the correlation of sales per agent and order profit per order by quarter. Result indicates sales per 
agent and total order profit per order are positively correlated with each other. Sales per Agent and Order Profit Per Order diverged the 
most during Quarter 1 and Quarter 4. Sales per Agent were $2,603,758.43 higher than Order Profit Per Order during Quarter 1. 
The decrease sales made by international sales agent cause order profit per order become decrease.

-  Sales & Delivery Status & Shippingg Delivery Risk
  <img width="264" height="302" alt="image" src="https://github.com/user-attachments/assets/b6db46a0-2844-4ba4-9a74-0e746748f344" />

#### Achieved Reserch Objectives (2) : Identified fraudulent suppliers buying pattern.

1. <img width="673" height="443" alt="image" src="https://github.com/user-attachments/assets/4e6a92a7-c5b6-4241-92d0-815ee8a19c29" /> <br>
Line and clustered column chart allow various series to be directly compared. The figure above describes the benefit of suspected 
fraudulent suppliers order and total sales per agent are negatively correlated with each other. International sales agent achieves the 
highest sales during May ($71592.11 million dollars) while the total 46 benefit of suspected fraudulent suppliers order is during August
($96662.56 million dollars). This indicates the increase fraudulent suppliers order can cause the total sales made by international sales
agent drop.

2. <img width="592" height="729" alt="image" src="https://github.com/user-attachments/assets/9b94e7b9-ef85-4d8f-8475-451a190d5e4e" /> <br>
Table chart shows the fraudulent users buying pattern. It includes the record of agent staffs name on duty, the supplier id, and how 
many times the fraudulent suppliers repeating their fake orders. Result founds the fraudulent suppliers has repeat their fake orders 
up to 22 times attempt. The repeat order column is formatted by yellow colour according to the minimum, center and maximum 
value. It will become darker yellow for the maximum value of repeat order. This chart assists users to identify fraud customers across 
multiple tiers of supply chain business. Detecting one of the supply chain risk factors at early stage can lower the tendencies of fraud 
buyer among suppliers.
