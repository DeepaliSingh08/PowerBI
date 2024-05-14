# Sales-Dashboard


## Problem Statement

Develop a comprehensive store sales dashboard report that provides insights into the performance of each store and the overall sales trends. The dashboard should be user-friendly, visually appealing, and interactive, allowing stakeholders to explore data efficiently.

To contribute to the success of a business by utilizing data analysis techniques,specifically focusing on time series analysis,to provide valuable insights and accurate sales forecasting.


### Steps followed 

- Step 1 : get data into Power BI Desktop, dataset is a excel file.
- Step 2 : Transform Data , Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" ,check"data types",check"header" & check"duplicates",check"every columns and replace as per reuirement",remove "Blank columns.
- Step 3 :Close and Apply ,cross check "dataset on right hand side".
- Step 4 :Choose cluster bar chart(category based on sales) and format
- Step 5 : create one more cluster bar chart(sub-category based on sales) and format
- Step 6 : create one more cluster bar chart(ship-mode based on sales) and format
- Step 7 : choose area chart(sales based on order date)for 2 years,choose month-level(use Legends).
- Step 8 :choose another area chart(Profit based on order date)for 2 years,choose month-level.
-Step 9 : choose map(sales in different states,put profit in Tooltip)
-Step 10 :choose donut chart(sales based on segment)
-Step 11 :choose donut chart(sales based on paymment mode)
- Step 12 : Visual filters (Slicers) were added for regions and format.
- Step 13 : add heading and format.
- Step 14 : add cards for sales,quantity,profit and format
- Step 15 : DAX query,in data view,add new column(AvgDelivery=DATEDIF('Sheet1'[Order Date],'Sheet1'[Ship Date],DAY))

- Step 16 : In the report view, refresh,new column added,choose one card ,average delivery by average value and format.

# Page2-Sale forecasting

- Step 1 : choose line chart(sales based on order date),break it as per daily sales
- Step 2 : click on chart > add further analyses then enable forecast and format .
- Step 3:right click on chart and select showed as table
- Step 4: zoom chart by creating duplicate and in format enable zoom slider.
- Step 5 : Choose cluster bar chart and in Filter select(Top 10 states based on sales) and format
- Step 6 :Data View>Table Tools>New Table ,Table name(Salesforecast=SUMMARIZE('Sheet1','[Order Date],"Total Sales",SUM(Sheet1[Sales]))
- Step 7: sort new table(ASC to Desc),cross check values with existing table.
        
 # Report Snapshot (Power BI DESKTOP)

 
# Dashboard_Page_1![Page_1](https://github.com/DeepaliSingh08/PowerBI/assets/58591719/b29aaa04-1227-4287-990b-8aef7db235d3)

# Dashboard_Page_2![Page_2](https://github.com/DeepaliSingh08/PowerBI/assets/58591719/f029334a-d15c-4e80-9b11-b41f0345b5e7)


# Insights

A double page report was created on Power BI Desktop.

- In october month profit > sales-order of quantity is more in october 
- In 2020,march profit increased by 4 times
-Customer prefer standard delivery(ship mmode)
- In sub-category Order quantity of phone is higher as compared to chair and binders
- In category sale of office supplies is higher then technology and furniture.
- 43% customers prefer cash on delivery.
- segment through consumer is higher(48.09%) then segment from corporate
- 15 days forecasting-4th jan 2021 (minimum order-1215,maximum order-9392,average order-5304)
