
# Fleet Mangment-Dashboard



## Problem Statement

This dashboard helps stakeholders to identify the most frequently used trucks along with their associated costs and sales.
It highlights explore ways to reduce expenses and increase profit by identifying the most costly drivers and replacing them with more cost-efficient ones. Additionally, we analyze routes to determine opportunities for transporting goods to closer destinations, which would help reduce fuel and maintenance costs.

The dashboard also includes Revenue analysis with root cause to Vehicle Analysis, Cost analysis,profit analysis



### Steps followed 

- Step 1 : Load data into Power BI Desktop From dataset is a Excel file.
![Extract](https://github.com/user-attachments/assets/65737408-9b78-4fe7-9a32-474cf62ae072)
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also Check Data Valid by use Captlize Each Word & Trim, detect Data type".
![Transformation](https://github.com/user-attachments/assets/475939d2-aed0-453b-8f17-51f5345328d0)

- Step 4 : Append queries to make Fact table".

![Transformation](https://github.com/user-attachments/assets/47a7bcd6-e804-4b37-a02e-24acd6630b75)


- Step 5 : load data into data model make star schema model to help us in calculation")

![load data](https://github.com/user-attachments/assets/86255795-ebd4-483d-867b-5bc40e66c12f)

Create Data Model 

![Data Model](https://github.com/user-attachments/assets/a1462b34-de7d-4751-bf4a-8188424229ac)

- Step 6 : make Caluclation by DAX .

![DAX](https://github.com/user-attachments/assets/3f99d5e5-d1ae-49b7-bcf7-969b631ff895)

- Step 7 : Build Revenue Dashboard 
Create Four Card (Revenue,Quantity,Weight (TON),Goods Value)
Which insights
Net Revenue Over time
Net Revenue By Trucks
Top City By Net Revenue 


![Revenue Dashboard](https://github.com/user-attachments/assets/b39fdbab-319a-440d-a514-4d2704318ad9)
. 
- Step 8 : Visual filters (Slicers) were added for Two fields named "Year", "Trailers".

![year-over-year](https://github.com/user-attachments/assets/4371d401-53f0-4489-b038-84dabf05ca23))

- Step 9 : Create Root Cause analysis for Vechile To Know More detailed to each Trucks.

![Image](https://github.com/user-attachments/assets/a55515d0-a8b1-4430-88a4-560b4ea6456f)


           
- Step 10 : Build Cost Dashboard 
Create Four Card (Cost,Cost per Km,Cost per Weight,Daily Cost)
Which insights

Cost Over time
Cost per KM by Trucks
Daily Cost by Trucks
Cost by Trucks

![Image](https://github.com/user-attachments/assets/e654a163-d2ee-4651-a579-fe0aef075965)



-  Visual filters (Slicers) were added for Two fields named "Year", "Trailers".

- Step 13 : Bulild Profit Dashboard
Create Four Card (Profit,Profit per Km,Profit per Weight,Daily Profit)
Which insights

Profit Over time
Profit per KM by Trucks
Daily Profit by Trucks
Profit by Trucks



![Image](https://github.com/user-attachments/assets/fabb0c5d-b8ca-433b-99a1-b1598926bf87)
