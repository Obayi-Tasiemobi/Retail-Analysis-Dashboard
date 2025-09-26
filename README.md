# Retail_Store_Data_Analysis (Interactive Dashboard created using MS Excel)

## Project Objective
The aim of this project is to demonstrate data cleaning, exploration, and analysis. Also, to track the progress of sales/profit across both years.

## Outline
- Data cleaning and preparation	
- Category and Product analysis
- Customer and Market insights
- Time series and trend

## Steps
- Data cleaning to remove irregularities
- Use of excel functions to find total cost, revenue, total revenue (after discount) and profit
- Pivot tables for summary and aggregations
- Created charts for visualization
- Designed dashboard
- Created slicers to make the dashboard interactive

## Project problems
- Revenue and profit by category
- Top 5 best-selling product by revenue and profit
- Customer segment with the highest revenue and profit
- Region with highest revenue and profit
- Region and customer segment with highest order
- Payment method most used
- How sales trends vary monthly and yearly
- Trend of orders by region overtime

## Data Cleaning and Preparation
- Handling missing data: Found 34 blank/missing values from three different columns (Product, Category, and Payment method). I filtered the category column to see only the missing values. I checked each product and filled in the category it belonged to. The most frequent (mode) product and payment methods were used to fill in the missing values. E.g. I filled in smartphone which is the most frequent product into blank cells that fall under electronic category; the most frequent payment method used by small business is Debit card etc.  
- Duplicates: Thirty (30) duplicates values were found and removed from the OrderID column leaving 1,700 unique values
- Find and Replace: correction of the typos in the Region column (Est-East, Norrth-North, Sout-South, and Wst-West)
- Use of excel formulas to find total cost, revenue before discount, discount amount, total revenue after discount, and profit

## KPIs
- Total Revenue	$2,845,958 (YoY -2%)
- Profit		$760,700 (YoY -6%)
- Profit margin	27%
- Quantity	8506
- Total Order	1700

## Category and Product overview
- Fashion category generated the highest revenue and profit with a total revenue of $640,166 (22.5% of total revenue) and $171,989 (23% of total profit) while Stationary is lowest in both revenue and profit with a total of $332,915 (11.7% of total revenue) and $89,864 (12% of total profit). 
- Top five (5) best-selling products both in revenue and profit are; Blender, Smartphone, Jeans, Office Chair, and T-Shirt. Blender is the highest in both revenue ($232,262) and profit ($65,363) while Pen is the lowest in both with revenue as $154,705 (5%) and $44,038 (5.8%) as profit.

## Customer and Market insights
- Consumer generated $1,002,767 (35.2%) as revenue and $275,083 (36.2%) as profit, making it the customer segment highest in both revenue and profit. Corporate made $890,383 (31.2%) and $237,966 (31.3%) respectively, making it the lowest in both revenue and profit.
- The south region made it to the top with revenue as $757,514 (26.6%) and profit as $203,556 (26.8%). On the other hand, East region made the lowest revenue of $686,204 (24%) while West region generated the lowest profit with a total of $183,848 (24.2%). All four regions are closely matched
- Small Business segment and West region record the highest order. This implies repeated purchases. 
Payment method most used is Debit card

## Time Series and Trend
- January ranks highest in both revenue and profit ($282,963 and $75,949) while June ranks lowest in both ($219,4553 and $51,224). All months are closely matched but the top five are Jan, May, Apr, Oct, and Feb. These months show peak in demand; promotional campaigns will boost sales in these months.
- 2023 performed better than 2024 in both revenue and profit. There is 2% decrease in revenue and 6% decrease in profit.
- In 2023, West region records the highest order (241) while East has the lowest order (200). In 2024, South records the highest order (217) while east has the lowest too (195)

## Suggestion
Discount increases the chances of returning customers and increased sales but, it should not affect total revenue and profitability. The total cost of goods, unit price, and quantity being purchased should be considered when giving discount so that revenue and profit will not be affected. Giving 20% discount for one single ordered product with 114.3 as cost and 151.2 as unit price will definitely affect revenue and profit. The discount given did not drive sales but reduced profit.
Investigation should be conducted to ascertain the reason(s) for the decrease in revenue and profit is 2024. Also, low performance of category/product especially Stationary. It could be ineffective marketing, reduced product quality, increased competition, economic condition or change in market trend. Customer survey could help identify the root cause.

## Extra 
The timeline and slicer in the dashboard show more breakdown of the product performance in both years, months each product sold highest, performance across the four regions in both years, and customer segments. It reveals a lot of information about the dashboard which are not seen at the first glance  

After the whole process of data cleaning, exploration, analysis and dashboard creation, we have been able to provide data-driven actionable insights that enables informed decisions.


