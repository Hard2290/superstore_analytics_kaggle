# Superstore Sales Analytics - Power BI

- Data Source : Superstore dataset from kaggle : https://www.kaggle.com/datasets/bitricks/superstore-dataset

- The Dataset contains 3 tables:
    - Orders Table - contain all the details of orders, i.e., location, time, category, profit/sales, etc.
    - People Table - contain names and designated regions of all the Regional Managers of the store.
    - Returns Table - contain order ID of all the returned orders.
- Sales data is available from January, 2020 to December, 2023.

## Problem Statement :
- Create and show the following KPIs for current year and previous year : 
    - Sales
    - Profit
    - % Returned Orders
- Create metrics showing % change of all the KPIs for current vs previous year.
- Compare Sales performance versus previous year over time.
- Determine the most profitable product and the most loss making product.
- Determine the place where most of the profit is happening.
- Visualize Sales by Segments

## Tools used :
- Microsoft Power BI

## Supersales Dashboard :
- Sales department can analyze sales, profit and % returned orders through this dashboard.
- It analyses the sales and profit with respect to different products, segments, regions in USA and Canada.
- The report also provide insights on current versus previous year sales, profit and % returned orders.

![Image](https://github.com/user-attachments/assets/0a84eb28-4c46-4bec-845f-a3e46e71430e)

#### Slicer Panel :
- To open it -> click on the filter icon on top right.
- To Hide it -> click on the white left arrow on top of the slicer folder.

![Image](https://github.com/user-attachments/assets/c3bcf137-e2be-443e-824d-740a75f34cd9)

![Image](https://github.com/user-attachments/assets/21bc6db6-6919-4ca6-834e-e1252392672b)

- Using these 4 slicers, we can filter out available visual insights for different regions and product segments for various data ranges.
- we can even personalize the report for a specific customer over various data ranges.

#### KPIs :

![Image](https://github.com/user-attachments/assets/e76863f4-789c-4139-9d73-9d8fd6e9f7ff)

- A Card visual has been created showing various KPIs for current and previous year. 
- Conditional color formatting has been applied showing % change of KPI values for current vs previous year in favor of (Green) or against (Red) the store.
- The store has made a total sales of $2.33 Millions from 2020 to 2023, which is 47.16 % higher than total sales from 2020 to 2022.
- It has made a total profit of $292.30K from 2020 to 2023, which is 48.85 % higher than previous years profit.
- There has been 2.95 % reduction (in favor of the store - showing in Green) in the % returned orders for the current year 2023 as compared to previous years, 2020 to 2022.

#### Sales vs Previous Year over time :

![Image](https://github.com/user-attachments/assets/5a33bb7e-4ce5-4366-a86a-b024c3dce769)

- The above Line visual is showing Sales performance over time for current and previous years.
- Solid green line is showing current sales and dotted grey line is showing previous year sales over time.
- For the year 2021, sales performance was slightly lower than that of the previous year, 2020.
- After 2021, on an average, the sales performance is higher as compared to previous years.
- Overall there has been a rising trend in sales performance over time.

#### Profit by Product :

![Image](https://github.com/user-attachments/assets/698f87b6-334b-4f7e-b9b8-7990b12c8a9e)

- This stacked column chart is showing total profit attained by various products in the store.
- Conditional color formatting gradient has been used to show most profitable in Greener tone and least profitable in Reddish tone, while the average in Greyish tone.
- The most profitable products are "Copiers" under "Technology" segment accounting for total profit of around $56K.
- The least profitable products are "Tables" under "Furniture" segment accounting for total loss of around $17K.
- Apart from "Bookcases" and "Tables" under "Furniture" segment, all products are making profit, with "Technology" segment being most profitable.

#### Profit by State :

![Image](https://github.com/user-attachments/assets/fe02d57d-5ba7-4983-a0e9-818ed9ceeb40)

![Image](https://github.com/user-attachments/assets/bcafb480-e293-4197-8d6c-2ea6b8e8860a)

- The map visual is showing profit distribution across various states in USA and Canada.
- Using conditional color formatting, most profitable states are shown in greenish tone and least ones are shown in greyish tone.
- The most profitable states are "California" and "New York" in USA accounting for total profits of around $76K and $74K respectively.
- Among USA and Canada, USA stores have very high total Sales and profit, hence, demand is very high in USA.

#### Sales by Segment :

![Image](https://github.com/user-attachments/assets/fbe76445-c248-4842-ba8f-2b5051dfc20b)

- 
