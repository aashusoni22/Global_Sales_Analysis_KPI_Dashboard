# Global_Sales_Analysis_KPI_Dashboard


Link to Interactive Power BI Dashboard:
https://app.powerbi.com/reportEmbed?reportId=69ccbe1a-8a76-481b-9e97-275bee768fb5&autoAuth=true&ctid=f651bb08-d47e-4082-9eac-58ea3ae7ad1f

![Screenshot 2022-11-18 172553](https://user-images.githubusercontent.com/114427519/202829739-51b363d1-3914-4056-af90-76d5a815b11d.jpg)



- Objective: To analyze spending trends to find ways to build out healthy lifestyle.

- Questions to Answer in order to achieve the Goal: 
  - “On which item the most money has been spend in 2021? And does that fulfill the current Goal?” 
  - “Where the credit card has been mostly used? Is it for in-store purchases or online?”
	“Where the credit card has been mostly used? Is it for online food order for fast food purchases or grocery store for healthy food?”
	“In total, how much money has been used from total yearly limit of $15600?”
	“Did the due payments were paid on time? If not, how much interest charged in 2021?”
•	Data Exploration and Data Cleaning:
	Extracted personal credit card statement from 2021 in CSV format to perform data analysis.
	Performed Data Exploration in Excel to get an overall idea about dataset and data type present.
	Executed Data Cleaning in Excel to aligned data, converted date to short date format and amount as numbers for ensuring data consistency.
	To better analyze data, categorized all items into three categories Purchased, Payment, Interest & Cash back using IF NESTED function in Excel.
•	Data Extraction & Data Analysis:
	Imported cleaned dataset into Microsoft SQL Server Management Studio for analyzing.
	Extracted data from dataset using SQL queries.
	Performed analysis using various SQL functions such as Aggregated functions – SUM, LIKE operator, CTEs, MONTH, YEAR, DISTINCT, GROUP BY, CASE WHEN, Aliases. 
	Created Views to form a virtual table to only use specific part of dataset to answer the question.
•	Data Visualization:
	Develop clear visualizations to convey complicated data in a clear and concise manner.
	Used Tableau Desktop to import .xlsx for data visualization.
	Created visualization by creating dashboard which includes bar chat, line charts for comparison, Important KPIs and filters.
•	Data Insights found through visualization: 
	In 2021, The most money was spent on online food orders.
	When reviewing and analyzing data trends for online & In-store purchases, most purchases were online rather than in-store.
	From credit limit of $15600 (yearly) only used 46.2% of the limit which is $7216. 
	So, by considering overall spending trend I think to live a healthy lifestyle I should avoid online food ordering and go to grocery store to buy stuff that can lead to a small walk and healthy homemade food. Same applies to online/In-store purchases as well.
